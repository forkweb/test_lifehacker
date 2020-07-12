<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
      <Landing></Landing>
  </div>
</template>

<script>
import Landing from './components/Landing.vue'
import animateScrollTo from 'animated-scroll-to';
import jQuery from "jquery";


export default {
  name: 'App',
    components: {
    Landing
  },
  watch: {
    animateScrollTo() {
      this.animateScrollTo();
    }
  },
  methods: {
    animateScrollTo(){
      animateScrollTo(0).then(hasScrolledToPosition => {
        // scroll animation is finished

        // "hasScrolledToPosition" indicates if page/element
        // was scrolled to a desired position
        // or if animation got interrupted
        if (hasScrolledToPosition) {
          // page is scrolled to a desired position 
        } else {
          // scroll animation was interrupted by user
          // or by another call of "animateScrollTo"
        }
      });
    },
    fixedMenu(){
      (function($) {
        $(window).bind('scroll', function() {
        var navHeight = $( window ).height() - 30;
          if ($(window).scrollTop() > navHeight) {
            $('.header-nav').addClass('fixed');
            $('.section1-nav').addClass('fixed');
          }
          else {
            $('.header-nav').removeClass('fixed');
            $('.section1-nav').removeClass('fixed');
          }
      });
      })(jQuery);
    },
    animate_text() {
      console.log("test");
    },
  },
  create(){
    this.animateScrollTo();
  },
  mounted() {
    // this.animate_text();
    this.animateScrollTo();
    this.fixedMenu();

    
  },
}
</script>

<style lang="scss" type="text/scss">
  @import "./style/main.scss";
  @import "./style/adaptive.scss";
</style>
