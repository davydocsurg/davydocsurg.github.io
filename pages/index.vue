<template>
  <div class="">
    <div class="container">
      <Hero />
      <hr class="bg-success" />
      <About />
      <hr class="bg-success" />
      <Proficiency />
      <hr class="bg-success" />
      <Skills />
      <hr class="bg-success" />
      <Experience />
      <hr class="bg-success" />
      <Projects />
      <hr class="bg-success" />
      <Socials />
      <hr class="bg-success" />
      <FooterD />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Hero from "~/components/Hero.vue";
import About from "~/components/About.vue";
import Proficiency from "~/components/Proficiency.vue";
import Scroll from "~/animations/scroll";
import Skills from "~/components/Skills.vue";
import Experience from "~/components/Experience.vue";
import Projects from "~/components/Projects.vue";
import Socials from "~/components/Socials.vue";
import FooterD from "~/components/FooterD.vue";
// import "../assets/css/main.css";
// import "../assets/fontawesome-free/css/all.css";
Vue.directive("scrollAnime", Scroll);

export default Vue.extend({
  name: "IndexPage",
  components: {
    Hero,
    About,
    Proficiency,
    Skills,
    Experience,
    Projects,
    Socials,
    FooterD,
  },
});
</script>
