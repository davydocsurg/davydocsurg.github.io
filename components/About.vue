<template>
  <div id="about" class="container jst-abt p-4 mt-4">
    <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
      <h1 class="text-bold" v-scrollAnime>
        About <span class="text-success">Me</span>
      </h1>
      <div class="card bg-card col-md-12 col-lg-4 shadow-sm" v-scrollAnime>
        <span class="p-1">A few facts about myself...</span>
      </div>
      <br />
      <br />
      <div class="col-lg-8 col-md-12 col-sm-12 col-xs-12">
        <p class="lh-lg" v-scrollAnime>
          I'm a <span class="text-success">Full Stack Developer</span>,
          <span class="text-success">Blockchain Enthusiast</span> and
          <span class="text-success"> Enthusiastic Entrepreneur</span>
          <!-- with years of experience in the Tech industry. -->
          with strong troubleshooting skills and proven experience in creating
          and designing software in a
          <span class="text-success"> test-driven environment</span>.
          <br />
          I'm passionate about <span class="text-success">Startups</span> and
          gained most of my knowledge through self-tutoring.
          <!-- <span class="text-success"> Full-stack developer</span> with strong
          troubleshooting skills and proven experience in creating and designing
          software in a
          <span class="text-success"> test-driven environment</span>. Thrives
          and adapts to challenges in startup environments. An excellent
          communicator with the ability to stick to deadlines and quickly
          resolve issues.
          <br /> -->
          <!-- Having a strong belief in being 100% efficient, I devote my best to
          every laid down goals. -->

          Having a strong belief in being
          <span class="text-success">100 percent</span> efficient, I put up my
          best effort toward all of my objectives.

          <!-- I am a firm believer in being 100 percent efficient, so I give everything I have to each of the objectives I set.  -->
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="css" scoped>
.lh-lg {
  font-weight: 400 !important;
  font-size: 1.2rem !important;
}
.text-bold {
  font-weight: 300;
  font-size: 4.5rem;
}

p {
  line-height: 30px !important;
  font-size: 15px !important;
}

@media screen and (max-width: 992px) {
  .jst-abt {
    text-align: center !important;
  }

  .text-bold {
    font-weight: 300;
    font-size: 3.5rem;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateX(80px);
  transition: all 1.4s ease-out;
}

.enter {
  opacity: 1;
  transform: translateX(0px);
}
</style>
