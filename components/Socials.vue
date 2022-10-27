<template>
  <div class="container jst-soc" id="contacts">
    <SocText></SocText>

    <div class="boxes">
      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-github"></i>
          <!-- GitHub  -->
          :
        </span>
        <a
          id="github"
          href="https://github.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          >@davydocsurg</a
        >
      </div>
      <b-popover
        target="github"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-white"
          ><i class="fab fa-github"></i> GitHub</template
        >
        <a
          href="https://github.com/davydocsurg"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://github.com/davydocsurg
        </a>
      </b-popover>

      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-gitlab"></i>
          <!-- GitHub  -->
          :
        </span>
        <a
          id="gitlab"
          href="https://gitlab.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          >@davydocsurg</a
        >
      </div>
      <b-popover
        target="gitlab"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-white"
          ><i class="fab fa-gitlab"></i> Gitlab</template
        >
        <a
          href="https://gitlab.com/davydocsurg"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://gitlab.com/davydocsurg
        </a>
      </b-popover>

      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-twitter"></i>
          <!-- Twitter  -->
          :
        </span>
        <a
          id="twitter"
          href="https://twitter.com/davydocsurg"
          target="_blank"
          rel="noopener noreferrer"
          >@davydocsurg</a
        >
      </div>
      <b-popover
        target="twitter"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-primary"
          ><i class="fab fa-twitter"></i> Twitter</template
        >
        <a
          href="https://twitter.com/davydocsurg"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://twitter.com/davydocsurg
        </a>
      </b-popover>

      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-linkedin"></i>
          <!-- LinkedIn  -->
          :
        </span>
        <a
          id="linkedin"
          href="https://www.linkedin.com/in/davydocsurg/"
          target="_blank"
          rel="noopener noreferrer"
          >David Chibueze Ndubuisi</a
        >
      </div>
      <b-popover
        target="linkedin"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-white"
          ><i class="fab fa-linkedin"></i> LinkedIn</template
        >
        <a
          href="https://linkedin.com/in/davydocsurg"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://linkedin.com/in/davydocsurg
        </a>
      </b-popover>

      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-dev"></i>
          <!-- LinkedIn  -->
          :
        </span>
        <a
          id="devto"
          href="https://www.dev.to/davydocsurg/"
          target="_blank"
          rel="noopener noreferrer"
          >@davydocsurg</a
        >
      </div>
      <b-popover
        target="devto"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-white">
          <i class="fab fa-dev"></i> Dev.to
        </template>
        <a
          href="https://dev.to/davidchibueze"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://dev.to/davidchibueze
        </a>
      </b-popover>

      <div v-scrollAnime>
        <span class="text">
          <i class="fab fa-facebook"></i>
          :
        </span>
        <a
          id="facebook"
          href="https://www.facebook.com/davydocsurg/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Chibueze</a
        >
      </div>
      <b-popover
        target="facebook"
        class="text-center"
        triggers="hover"
        placement="top"
        variant="dark"
      >
        <template #title class="text-white"
          ><i class="fab fa-facebook"></i> LinkedIn</template
        >
        <a
          href="https://facebook.com/davydocsurg"
          class="text-dark pops"
          target="_blank"
          rel="noopener noreferrer"
        >
          https://facebook.com/davydocsurg
        </a>
      </b-popover>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import SocText from "./SocText";

export default Vue.extend({
  components: {
    SocText,
  },
});
</script>

<style lang="css" scoped>
.text-bold {
  font-weight: 300;
  font-size: 4.5rem;
}

b-popover {
  background: #0d1117 !important;
  text-align: center !important;
}

.boxes {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  align-items: center;
  margin-top: 1rem;
}
.boxes div {
  font-size: 2rem;
  border: 3px #a4a5a6 solid;
  padding: 1.5rem 2.5rem;
  margin-bottom: 3rem;
  transition: all 0.5s ease-out;
}
.boxes div:hover {
  padding: 0.5rem 1.5rem;
  background: #28a745 !important;
  color: #fff !important;
}
.boxes div:hover span {
  color: #000;
}

a {
  text-decoration: none !important;
  color: #a4a5a6 !important;
}

a:hover {
  color: #fff !important;
}

.pops {
  color: #28a745 !important;
}

@media screen and (max-width: 992px) {
  .jst-soc {
    text-align: center !important;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateY(100px);
  transition: all 1s ease-out !important;
}

.enter {
  opacity: 1;
  transform: translateY(0px);
}
</style>
