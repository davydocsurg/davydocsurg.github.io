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
            <!-- I design responsive and stunning web pages/SPAs using various UI frameworks and libraries -->
            Using various UI frameworks and libraries, such as
            <i class="text-success">Bootstrap</i>,
            <i class="text-success">Tailwind CSS</i>,
            <i class="text-success">VueJS/NuxtJS/VuetifyJS</i>,
            <i class="text-success"> ViteJS</i>,
            <i class="text-success"> ReactJS</i> and
            <i class="text-success"> MaterialUI</i>, I create responsive and
            attractive web pages/SPAs.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Back-end Development</h5>
          <p class="lh-lg">
            I develop highly extensible web applications with fast, solid, and
            secure APIs. My stack include <i class="text-success">PHP</i>,
            <i class="text-success">JavaScript</i>,
            <i class="text-success">TypeScipt</i>,
            <i class="text-success">Laravel</i>, and
            <i class="text-success">Nodejs</i>.
          </p>
        </div>
        <div class="mt-5" v-scrollAnime>
          <h5 class="text-success prof_head">Database Development</h5>
          <!-- I design uniformed relational data models aptly accomplished with -->
          <p class="lh-lg font-monospace">
            I design consistent relational data structures that are
            well-executed with
            <i class="text-success">MySQL</i>/<i class="text-success">SQL</i>
            and <i class="text-success">MongoDB</i>.
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
  .jst-prof {
    text-align: center !important;
  }

  .text-bold {
    font-weight: 400;
    font-size: 2.5rem !important;
    text-align: center !important;
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
