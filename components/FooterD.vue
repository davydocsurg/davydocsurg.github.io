<template>
  <div class="container footcont" id="footer">
    <footer class="row text-center justify-content-center">
      <div class="col-12 mb-5 text-center">
        <h3 class="text-center">Let's work together!</h3>
        <code class="text-success text-center">I'm available remotely</code>
        <br />
        <div class="badge badge-dark p-3">
          <i class="far fa-envelope"></i><span class="ml-1">E-mail me: </span>
          <!-- <br /> -->
          <a
            href="mailto:davydocsurg@gmail.com"
            class="mail-to font-weight-bolder"
            ><b>davydocsurg@gmail.com</b></a
          >
        </div>
      </div>

      <div
        class="col-lg-6 col-md-6 col-sm-12 col-xs-12 text-foot"
        v-scrollAnime
      >
        ©️ <b id="currentYear"></b>. David Chibueze
        <b class="text-success">Ndubuisi</b>
        <br />
        <br />
      </div>
      <div class="jst mx-auto" v-scrollAnime>
        <a
          href="https://github.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          class="mr-3"
          v-scrollAnime
        >
          <i class="fab fa-github foot"></i>
        </a>

        <a
          href="https://www.linkedin.com/in/davidchibueze/"
          target="_blank"
          rel="noopener noreferrer"
          class="mr-3"
          v-scrollAnime
        >
          <i class="fab fa-linkedin foot"></i>
        </a>

        <a
          href="https://twitter.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          class="mr-3"
          v-scrollAnime
        >
          <i class="fab fa-twitter foot"></i>
        </a>
        <a
          href="https://www.facebook.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          class="mr-3"
          v-scrollAnime
        >
          <i class="fab fa-facebook foot"></i>
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
import Vue from "vue";
import "./footer";

export default Vue.extend({
  data() {
    return {
      date_: "",
    };
  },

  mounted() {
    getCurrentYear();
  },

  methods: {},
});
</script>

<style lang="css" scoped>
.jst {
  margin-bottom: 2rem;
}

.mail-to {
  color: #fcfdfd;
}

.mail-to:hover {
  color: rgb(26, 192, 26);
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateY(50px);
  transition: all 2s ease-out;
}

.enter {
  opacity: 1;
  transform: translateY(0px);
}

.foot {
  font-size: 40px !important;
  color: aliceblue;
}

.foot:hover {
  color: #28a745;
}

@media screen and (max-width: 992px) {
  .footcont {
    /* text-align: center !important;
    justify-items: center !important; */
  }

  .jst {
    text-align: center !important;
    justify-items: center !important;
  }

  .text-foot {
    text-align: center !important;
    justify-items: center !important;
  }
}
</style>
