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
import WOW from 'wow.js';


export default {
  name: 'App',
    components: {
    Landing
  },
  watch: {
    animateScrollTo() {
      this.animateScrollTo();
    },
    wowJs() {
      this.wowJs();
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
          this.addClass("active");
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
    animate_img() {
      (function($)  {
        $(".header-barrels").hover(function(){
          $(this).find("img").addClass("animate__shakeX");
          $(this).find("img").addClass("animate__animated");
        },function(){
          $(this).find("img").removeClass("animate__shakeX");
          $(this).find("img").removeClass("animate__animated");
        });
      })(jQuery);
    },
    wowJs() {
      new WOW().init();
    }
  },
  create(){
    this.animateScrollTo();
    // this.wowJs();
  },
  mounted() {
    this.animate_img();
    this.animateScrollTo();
    this.fixedMenu();
    this.wowJs();

    
  },
}
</script>

<style lang="scss" type="text/scss">
  @import "./style/main.scss";
  @import "./style/adaptive.scss";
  @import "./style/animate.min.css";
</style>
