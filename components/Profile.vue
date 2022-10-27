<template>
  <div class="profile-pics" v-scrollAnime></div>
</template>

<style lang="css" scoped>
@media screen and (max-width: 767px) {
  .profile-pics {
    height: 200px !important;
    width: 200px !important;
    /* text-align: center !important; */
    /* justify-self: center !important; */
  }
}

.before-enter {
  opacity: 0 !important;
  transform: scale(0.5) rotateZ(0deg) !important;
  transition: all 2.4s ease-out !important;
}

.enter {
  opacity: 1 !important;
  transform: scale(1) rotateZ(0deg) !important;
}
</style>
