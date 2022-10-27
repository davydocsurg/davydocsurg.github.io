<template>
  <div class="container jst-skl b-4 mt-4" id="skills">
    <SkillText class="text-cente"></SkillText>
    <div class="row">
      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-html5 text-danger skill-icons"></i>
        <br />
        <span class="badge badge-danger badge-pill"> HTML5 </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-css3-alt text-primary skill-icons"></i>
        <br />
        <span class="badge badge-primary badge-pill"> CSS3 </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-js-square text-warning skill-icons"></i>
        <br />
        <span class="badge badge-warning badge-pill"> JavaScript </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <img
          src="../assets/svgs/ts.png"
          alt="TypeScript"
          width="70"
          srcset=""
        />
        <br />
        <br />
        <span class="badge badge-info badge-pill"> TypeScipt </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-php text-info skill-icons"></i>
        <br />
        <span class="badge badge-info badge-pill"> PHP </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-bootstrap text-indigo skill-icons"></i>
        <br />
        <span class="badge badge-indigo text-white badge-pill">
          Bootstrap
        </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-sass text-danger skill-icons"></i>
        <br />
        <span class="badge badge-danger badge-pill"> SCSS </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <!-- <b class=" text-info" style="font-size: 2rem !important">TailwindCSS</b> -->
        <img src="../assets/svgs/tailwindcss.svg" alt="" width="70" srcset="" />

        <br />
        <span class="badge badge-info badge-pill"> TailwindCSS </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-vuejs text-success skill-icons"></i>
        <br />
        <span class="badge badge-success badge-pill"> VueJS </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <br />
        <img src="../assets/svgs/vite.svg" alt="ViteJS" width="70" srcset="" />
        <br />
        <span class="badge badge-indigo text-white badge-pill"> ViteJS </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-react text-info skill-icons"></i>
        <br />
        <span class="badge badge-info badge-pill"> ReactJS </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-laravel text-danger skill-icons"></i>
        <br />
        <span class="badge badge-danger badge-pill"> Laravel </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-node-js text-success skill-icons"></i>
        <br />
        <span class="badge badge-success badge-pill"> Nodejs </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <img
          src="../assets/svgs/sql.png"
          alt="SQL/MySQL"
          width="70"
          class="sql_"
          srcset=""
        />
        <br />
        <span class="badge badge-warning badge-pill"> SQL/MySQL </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <img
          src="../assets/svgs/mongodb.png"
          alt="MongoDB"
          width="70"
          class=""
          srcset=""
        />
        <br />
        <span class="badge badge-success badge-pill"> MongoDB </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-git-alt text-danger skill-icons"></i>
        <br />
        <span class="badge badge-danger badge-pill"> Git </span>
      </div>

      <div class="col-lg-3 col-md-4 col-sm-6 text-center mt-4" v-scrollAnime>
        <i class="fab fa-linux text-warning skill-icons"></i>
        <br />
        <span class="badge badge-light text-dark badge-pill"> Linux </span>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import SkillText from "./SkillText.vue";

export default Vue.extend({
  components: {
    SkillText,
  },

  data() {
    return {
      progress_data: [
        { id: 1, name: `HTML 5`, width: "97", val: "97", level: 97 },
        { id: 2, name: "CSS 3", width: "90", val: "90", level: 90 },
        { id: 3, name: "Bootstrap 5", width: "87", val: "87", level: 87 },
        { id: 4, name: "Tailwind CSS", width: "75", val: "75", level: 75 },
        { id: 5, name: "JavaScript", width: "91", val: "91", level: 91 },
        { id: 6, name: "PHP", width: "82", val: "82", level: 82 },
        {
          id: 7,
          name: "VueJS/VuetifyJS",
          width: "89",
          val: "89",
          level: 89,
        },
        { id: 8, name: "Laravel 7", width: "77", val: "77", level: 77 },
        { id: 9, name: "SQL/MYSQL", width: "70", val: "70", level: 70 },
      ],
    };
  },

  methods: {},
});
</script>

<style lang="css" scoped>
/* #pic {
    background-image: url("../assets/img/tailwindcss.svg");
    width: 100%;
    background-repeat: no-repeat !important;
    height: 100%;
  } */
/* display: inline-block; */
.skill-icons {
  font-size: 5rem !important;
  text-align: center !important;
}

.sql_ {
  filter: invert(80%) sepia(70%) saturate(2023%) hue-rotate(352deg)
    brightness(100%) contrast(102%);
}

.text-indigo {
  color: blueviolet !important;
}

.badge-indigo {
  background: blueviolet !important;
}

.text-bold {
  font-weight: 300;
  font-size: 4.5rem;
}

.progress {
  height: 15px !important;
  transition: all 0.5s ease-out !important;
}

.progress-bar {
  transition: all 0.5s ease-out !important;
}

/* animes */
.before-enter {
  opacity: 1;
  transform: translateY(100px);
  transition: all 1.3s ease-out !important;
}

.enter {
  opacity: 1 !important;
  transform: translateY(0px) !important;
}

/* .slide-enter {
    opacity: 0;
  }

  .slide-enter-active {
    animation: slide-in 3s ease-out forwards;
    transition: opacity 1s;
  }

  .slide-leave {
  }

  .slide-leave-active {
    animation: slide-out 1s ease-out forwards;
    transition: opacity 1s;
    opacity: 0;
    position: absolute;
  }

  .slide-move {
    transition: transform 1s;
  }

  @keyframes slide-in {
    from {
      transform: translateY(20rem);
    }

    to {
      transform: translateY(0);
    }
  }

  @keyframes slide-out {
    to {
      transform: translateY(20px);
    }

    from {
      transform: translateY(0);
    }
  } */

@media screen and (max-width: 992px) {
  .jst-skl {
    text-align: center !important;
  }
}
</style>
