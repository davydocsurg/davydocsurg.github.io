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
            <small class="text-muted">Lagos, Nigeria - Remote</small>
            <br />
            <br />
          </div>

          <div class="col-lg-8">
            <ul class="list-style-type-none lh-lg">
              <li>
                Developed and maintained Coopco Technology's web applications
                and websites using HTML, CSS, JavaScript, VueJS, and ReactJS
              </li>

              <li>
                Proactively participated in the development process of multiple
                web applications
              </li>

              <li>
                Collaborated with the design team to ensure a seamless user
                experience across all devices and screen sizes
              </li>

              <li>
                Built reusable components and front-end libraries, reducing
                development time by 20%
              </li>

              <li>
                Optimized applications for speed and scalability, utilizing
                techniques such as lazy loading, code splitting, and image
                optimization, which reduced web page load time by 30%
              </li>
            </ul>
          </div>
        </div>
      </li>
      <br />
      <br />
      <li>
        <div class="container row">
          <div class="col-lg-4">
            <small class="">August 2022 - December 2022</small>
            <h5 href="" class="text-success">Nubela</h5>
            <small class="text-success">Freelance Technical Writer</small>
            <br />
            <small class="text-muted">Singapore - Remote</small>
            <br />
            <br />
          </div>
          <div class="col-lg-8">
            <!-- I worked as a freelance technical writer for Nubela which
            specializes in data enterprise and software development. During my
            time there, I was responsible for creating and editing technical
            blog posts and articles that were used to educate and inform the
            company's clients and potential clients about the services they
            offered.
            <br />
            My responsibilities included: -->

            <ul class="lh-lg">
              <li>
                Created and edited technical blog posts and articles for Nubela,
                specializing in data enterprise and software development.
              </li>

              <li>
                Conducted research and wrote technical articles and blog posts
                on various software development topics, such as web development,
                database design, and software testing.
              </li>

              <li>
                Utilized SEO best practices to increase website traffic and
                engagement.
              </li>

              <li>
                Collaborated with subject matter experts, developers, and
                stakeholders to ensure the accuracy and completeness of the
                content.
              </li>

              <li>
                Created clear and concise content for non-technical readers,
                while providing technical details for more advanced users.
              </li>
            </ul>
          </div>
        </div>
      </li>
      <br />
      <li>
        <div class="container row">
          <div class="col-lg-4">
            <small class="">April 2020 - May 2022</small>
            <h5 href="" class="text-success">Freelance Software Developer</h5>
            <small class="text-muted">Remote - Freelancer</small>
            <br />
            <br />
          </div>
          <div class="col-lg-8">
            Working with teams of skillful and experienced developers, I:
            <ul class="lh-lg">
              <li>
                Developed back-end and database infrastructures with over 90%
                security in collaboration with skillful and experienced
                development teams.
              </li>

              <li>
                Designed and implemented front-end components based on new and
                existing methods with a scalability rating of over 4 stars from
                users
              </li>

              <li>
                Assembled data on integration issues and vulnerabilities,
                reported findings and provided suggestions for improvement
              </li>

              <li>
                Tested troubleshooting methods, devised innovative solutions
                with a success rate of over 88%, and documented resolutions for
                inclusion in a knowledge repository for team support
              </li>

              <li>
                Conducted research, designed, and implemented scalable
                information identification, extraction, analysis, retrieval, and
                indexing applications
              </li>

              <li>
                Simplified the implementation of web applications by placing the
                application's structure onto the Laravel framework, reducing
                maintenance and new feature development time by a factor of 100
              </li>

              <li>
                Developed core server products in Laravel MVC and SOA service
                components for over 25 client sites, ensuring 99% compatibility
                with major browsers on both mobile and desktop platforms
              </li>

              <li>
                Created databases utilizing PHP8, PDO, and MySQL that optimized
                trucking performances, from creating, assigning, and tracking
                truckloads, increasing customer satisfaction to 85%.
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
                Participated proactively in the development process of multiple
                web applications during an internship at Innovation Growth Hub,
                Nigeria
              </li>
              <li>
                Resolved complex issues and conducted professional UI tests to
                optimize performance
              </li>

              <li>
                Conducted research on web development to contribute to projects
              </li>

              <li>
                Supported several instructors with the planning and organization
                of the IGHUB Developers and Entrepreneurs Fellowship
              </li>

              <li>
                Led group projects, ensuring 98% cooperation and effective
                teamwork
              </li>

              <li>
                Tutored small groups of students focused on specific parts of
                the fellowship.
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

@media screen and (max-width: 780px) {
  .lh-lg {
    font-size: 0.8rem !important;
    line-height: 1rem !important;
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
