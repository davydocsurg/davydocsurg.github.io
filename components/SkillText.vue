<template>
  <div>
    <h1 class="text-bold" v-scrollAnime>
      My <span class="text-success">Skills</span>
    </h1>
    <div class="card bg-card col-md-12 col-lg-8 shadow-sm" v-scrollAnime>
      <span class="p-1">
        Skills I've acquired so far.
      </span>
    </div>
  </div>
</template>

<style lang="css" scoped>
  .text-bold {
    font-weight: 300;
    font-size: 3.5rem !important;
  }

  @media screen and (max-width: 992px) {
    .jst-prof {
      text-align: center !important;
    }

    .text-bold {
      font-weight: 400;
      font-size: 2.7rem !important;
      text-align: center !important;
    }
  }

  /* animes */
  .before-enter {
    opacity: 0;
    transform: translateX(100px);
    transition: all 2s ease-out !important;
  }

  .enter {
    opacity: 1;
    transform: translateX(0px);
  }
</style>
