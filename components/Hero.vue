<!-- Please remove this file from your project -->
<template>
  <div class="container home-mt" id="home">
    <div class="row jst-space">
      <!-- <div class=" "> -->
      <div
        class="col-md-6 col-sm-12 col-xs-12 col-lg-6 text-center pics container"
      >
        <Profile />
        <!-- <div class="profile-pics" v-scrollAnime></div> -->
        <br />
      </div>
      <div class="col-md-6 col-sm-12 col-xs-12">
        <h1 class="">
          <p class="smaller" v-scrollAnime>David Chibueze</p>
          <span class="large text-success"><p v-scrollAnime>Ndubuisi</p></span>
        </h1>
        <b class=""
          ><p v-scrollAnime>
            Software Engineer <i class="fas fa-laptop-code"></i>
          </p>
        </b>

        <div class="mt-4">
          <div class="card bg-card shadow-sm p-3 mx-sm-auto" v-scrollAnime>
            <!-- <hr class="bg-white" /> -->

            <div class="row jst-space">
              <div class="col-sm-12">
                <div class="mr-4 mx-sm-auto">
                  <i class="fas fa-map-marker-alt"></i>
                  <span class="ml-1">Location</span>
                  <br />
                  <br />
                  <b>Abia, Nigeria</b>
                </div>
                <hr class="only-sm" />
                <div class="mr-4 mx-sm-auto">
                  <i class="fas fa-phone"></i><span class="ml-1">Phone</span>
                  <br />
                  <br />
                  <a href="tel:+2349013582063" class="mail-to">
                    <b class="cursor-pointer">+234 901 358 2063</b>
                  </a>
                </div>

                <hr class="only-sm" />
                <div class="mx-sm-auto">
                  <i class="far fa-envelope"></i
                  ><span class="ml-1">E-Mail</span>
                  <br />
                  <br />
                  <a href="mailto:davydocsurg@gmail.com" class="mail-to"
                    ><b>davydocsurg@gmail.com</b></a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Profile from "./Profile.vue";

export default Vue.extend({
  name: "Hero",
  components: { Profile },
});
</script>

<style lang="scss" scoped>
/* variables */
/* $whiteny= #a4a5a6; */

.chat-links {
  font-size: 4rem;
  padding-left: auto !important;
}

.cursor-pointer:hover {
  cursor: pointer;
  color: #28a745 !important;
}
.large {
  font-size: 5rem;
}

#modal-chat {
  background-color: #0d1117 !important;
}

.smaller {
  font-size: 3.9rem;
  font-weight: 300;
}

.jst-space {
  /* justify-content: space-between; */
  /* align-items: center; */
  /* justify-content: safe; */
}

.mail-to {
  color: #a4a5a6;
}

.mail-to:hover {
  color: rgb(26, 192, 26);
}

.avatar-4xl {
  height: 6.125rem !important;
  width: 6.125rem !important;
}
.avatar {
  /* position: relative; */
  display: inline-block !important;
}

.home-mt {
  margin-top: 4rem;
}

.profile-pics {
  height: 250px !important;
  width: 250px !important;
  background-image: url("../assets/img/prof.jpg");
  background-size: cover !important;
  background-position: center !important;
  border: solid 1px;
  border-radius: 205px;
}

@media screen and (max-width: 1023px) {
  .jst-space {
    text-align: center !important;
    /* display: block; */
    /* justify-content: center !important; */
    /* justify-items: center !important; */
    /* justify-self: center !important; */
  }

  .profile-pics {
    height: 230px !important;
    width: 230px !important;
    /* text-align: center !important; */
    /* justify-self: center !important; */
  }

  .large {
    font-size: 3rem !important;
  }
  /* .pics {
      text-align: center !important;
    } */
}

@media screen and (max-width: 767px) {
  .profile-pics {
    height: 200px !important;
    width: 200px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }
}

/* animes */
.before-enter {
  opacity: 0;
  transform: translateY(-100px);
  transition: all 2s ease-out;
}

.enter {
  opacity: 1;
  transform: translateY(0px);
}
</style>
