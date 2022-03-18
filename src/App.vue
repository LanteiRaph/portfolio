<template>
  <router-view />
  <div class="controlls" ref="controls">
    <router-link to="/">
      <div class="control control-1 active-btn" data-id="home">
        <i class="fas fa-home"></i>
      </div>
    </router-link>
    <router-link to="/about">
      <div class="control control-2" data-id="about">
        <i class="fas fa-user"></i>
      </div>
    </router-link>
    <router-link to="/portfolio">
      <div class="control control-3" data-id="portfolio">
        <i class="fas fa-briefcase"></i>
      </div>
    </router-link>
    <!-- <router-link to="/contact-me">
      <div class="control control-5" data-id="contact">
        <i class="fas fa-envelope-open"></i>
      </div>
    </router-link> -->
  </div>

  <div class="theme-btn">
    <i class="fas fa-adjust"></i>
  </div>
</template>
<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      controls: null,
    };
  },
  methods: {
    PageTransitions() {
      //Get the btn under the controls
      const sectBtn = this.controls.querySelectorAll(".control");
      //Button click active class
      for (let i = 0; i < sectBtn.length; i++) {
        sectBtn[i].addEventListener("click", function () {
          let currentBtn = document.querySelectorAll(".active-btn");
          currentBtn[0].className = currentBtn[0].className.replace(
            "active-btn",
            ""
          );
          this.className += " active-btn";
        });
      }

      //Toggle theme
      const themeBtn = document.querySelector(".theme-btn");

      themeBtn.addEventListener("click", () => {
          let element = document.body;
          element.classList.toggle("light-mode");
      });
    },
  },
  mounted() {
    //Get parent container for the controls
    this.controls = this.$refs.controls;
    //Activate the pageTransitions
    this.PageTransitions();
  },
};
</script>

<style  lang="scss">
</style>
