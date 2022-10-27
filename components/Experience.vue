<template>
  <div id="experience" class="container jst-prof">
    <div class="mb-5">
      <h1 class="text-bold" v-scrollAnime>
        Exper<span class="text-success">ience</span>
      </h1>

      <div
        class="card bg-card col-md-12 col-lg-4 shadow-sm jst-pro"
        v-scrollAnime
      >
        <span class="p-1 jst-prof">My experience so far...</span>
      </div>
    </div>
    <ul class="timeline" v-scrollAnime>
      <li>
        <div class="container row">
          <div class="col-lg-4">
            <small class="">June, 2022 - Present</small>
            <h5 href="" class="text-success">Coopco</h5>
            <small class="text-success">Frontend Engineer</small>
            <br />
            <small class="text-muted">Lagos, Nigeria.</small>
            <br />
            <br />
          </div>

          <div class="col-lg-8">
            <ul class="list-style-type-none lh-lg">
              <li>
                Worked in an agile environment with weekly standups, kept track
                of projects, and participated in 2 hours of Sprint Planning per
                week.
              </li>
              <li>Support planning and testing features.</li>

              <li>
                Excellent knowledge of security on the client side (CSRF, JWT,
                CORS).
              </li>

              <li>Implemented new features and improved existing ones.</li>

              <li>Optimization of existing features through profiling.</li>

              <li>Development of excellent PWAs.</li>

              <li>
                Acknowledged by my superiors as a diligent professional who
                completes all assigned tasks within the stipulated timeframe.
              </li>
            </ul>
          </div>
        </div>
      </li>
      <br />
      <li>
        <div class="container row">
          <div class="col-lg-4">
            <small class="">April 2020 - Present</small>
            <h5 href="" class="text-success">Freelance Software Developer</h5>
            <small class="text-muted">Remote - Freelancer</small>
            <br />
            <br />
          </div>
          <div class="col-lg-8">
            Working with teams of skillful and experienced developers, I:
            <ul class="lh-lg">
              <li>
                develop back-end and database infrastructures with more than 90%
                security.
              </li>

              <li>
                devise front-end components based on both new and existing
                methods which have received a scalability rating of more than 4
                stars from users.
              </li>

              <li>
                assemble data on integration issues and vulnerabilities and
                report all findings, including suggestions for improvement.
              </li>

              <li>
                test troubleshooting methods, devise innovative solutions with a
                success rate of more than 88%, and document resolutions for
                inclusion in a knowledge repository for our team support.
              </li>

              <li>
                conduct research, design, and implementation of scalable
                information identification, extraction, analysis, retrieval, and
                indexing applications.
              </li>

              <li>
                implement web applications by placing the structure of the
                application onto the Laravel framework. This simplifies
                maintenance and the development of new features by a factor of
                100.
              </li>

              <li>
                executed core server product development in Laravel MVC and SOA
                service components for more than 25 client sites to ensure 99%
                compatibility with major browsers on both mobile and desktop
                platforms.
              </li>

              <li>
                increased customer satisfaction to 85% by creating databases
                utilizing PHP8, PDO, and MySQL that optimized trucking
                performances from creating, assigning, and tracking truckloads.
              </li>
            </ul>
          </div>
        </div>
      </li>

      <li>
        <div class="container row">
          <div class="col-lg-4">
            <small class="">February, 2020 - April 2020</small>
            <h5 href="" class="text-success">Innovation Growth Hub</h5>
            <small class="text-success">Backend Developer - Intern</small>
            <br />
            <small class="text-muted">Abia, Nigeria.</small>
            <br />
            <br />
          </div>

          <div class="col-lg-8">
            <ul class="list-style-type-none lh-lg">
              <li>
                Proactively participated in the development process of multiple
                web applications
              </li>
              <li>
                Resolved complex issues, and performed professional UI tests to
                optimize performance
              </li>

              <li>
                Accumulated information on research web development to
                contribute to projects
              </li>

              <li>
                Supported several instructors with the planning and organization
                of the IGHUB Developers and Entrepreneurs Fellowship.
              </li>

              <li>
                Led group projects by ensuring 98% cooperation and effective
                teamwork.
              </li>

              <li>
                Tutored small groups of students focused on specific parts of
                our fellowship.
              </li>
            </ul>
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<style lang="css" scoped>
.lh-lg {
  font-weight: 400 !important;
  font-size: 1.2rem !important;
  line-height: 2rem !important;
}
.text-bold {
  font-weight: 300;
  font-size: 3.5rem !important;
}

@media screen and (max-width: 992px) {
  .jst-prof {
    text-align: left !important;
  }

  .text-bold {
    font-weight: 400;
    font-size: 2.5rem !important;
    text-align: left !important;
  }

  .timeline {
    text-align: left !important;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateX(180px);
  transition: all 1.2s ease-out !important;
}

.enter {
  opacity: 1;
  transform: translateX(0px);
}

ul.timeline {
  list-style-type: none;
  position: relative;
}
ul.timeline:before {
  content: " ";
  background: #d4d9df;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 400;
}
ul.timeline > li {
  margin: 20px 0 0 0;
  /* padding-left: 20px; */
}
ul.timeline > li:before {
  content: " ";
  background: #28a745;
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid white;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
</style>
