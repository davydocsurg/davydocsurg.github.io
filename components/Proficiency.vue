<template>
  <div id="proficiency" class="container jst-prof p-4 mt-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
      <h1 class="text-bold" v-scrollAnime>
        Profi<br class="break" /><span class="text-success">ciency</span>
      </h1>
      <div class="card bg-card col-md-12 col-lg-4 shadow-sm" v-scrollAnime>
        <span class="p-1">My areas of expertise...</span>
      </div>

      <!-- <div class="row"> -->
      <div class="col-lg-8 col-md-12 col-sm-12 col-xs-12 mt-4">
        <div class="" v-scrollAnime>
          <h5 class="text-success prof_head">Front-end Design</h5>
          <p class="lh-lg">
            I have extensive experience in developing web pages and single-page
            applications using a wide range of UI frameworks and libraries.
            These include popular options such as
            <code class="text-success">
              Bootstrap, Tailwind CSS, ReactJS, NextJS, VueJS, NuxtJS,
              VuetifyJS, ViteJS, and MaterialUI</code
            >. Leveraging my expertise in these tools, I am able to create
            highly responsive and visually appealing user interfaces that
            enhance the user experience and drive engagement.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Back-end Development</h5>
          <p class="lh-lg">
            I specialize in building robust and scalable web applications that
            feature fast, secure, and highly extensible APIs. My toolset
            includes a range of technologies, such as
            <code class="text-success">
              PHP, JavaScript, TypeScript, Laravel, and Node.js</code
            >. With a keen eye for detail and a passion for coding, I bring a
            wealth of experience and expertise to each project, ensuring that my
            solutions meet the highest standards of quality and performance.
            Whether working independently or as part of a team, I am dedicated
            to delivering innovative, cutting-edge applications that drive
            real-world impact and value.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Database Development</h5>
          <!-- I design uniformed relational data models aptly accomplished with -->
          <p class="lh-lg font-monospace">
            I possess the ability to design consistent and efficient relational
            data structures that are compatible with both
            <code class="text-success">MySQL/SQL and MongoDB</code> . My
            expertise in data modeling and database design ensures the accuracy,
            performance, and scalability of these structures, allowing for
            seamless data retrieval and storage.
          </p>
        </div>
      </div>
      <!-- </div> -->
    </div>
  </div>
</template>

<style lang="css" scoped>
.text-bold {
  font-weight: 300;
  font-size: 3.5rem !important;
}

.prof_head {
  text-decoration: underline;
}

.break {
  display: none !important;
}

p {
  line-height: 30px !important;
  font-size: 19px !important;
}

@media screen and (max-width: 992px) {
  /* .jst-prof {
    text-align: center !important;
  } */

  .text-bold {
    font-weight: 400;
    font-size: 2.5rem !important;
    /* text-align: center !important; */
  }
}

@media screen and (max-width: 300px) {
  .break {
    display: block !important;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateX(-80px);
  transition: all 1.4s ease-out;
}

.enter {
  opacity: 1;
  transform: translateX(0px);
}
</style>
