<template>
  <Header />
  <SubHeader />
  <Promo />
  <Descr />
  <Carousel />
  <Review />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import SubHeader from './components/SubHeader.vue'
import Promo from './components/Promo.vue'
import Descr from './components/Descr.vue'
import Carousel from './components/Carousel.vue'
import Review from './components/Review.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    SubHeader,
    Promo,
    Descr,
    Carousel,
    Review,
    Footer
  }
}
</script>

<style>
    @font-face {
      font-family: "GT Eesti Pro Display";
      src: url("fonts/GT\ Eesti\ Pro\ Display-Thin.woff2");
      font-style: normal;
      font-weight: 100;
    }

    @font-face {
      font-family: "GT Eesti Pro Display";
      src: url("fonts/GT\ Eesti\ Pro\ Display-Light.woff2");
      font-style: normal;
      font-weight: 200;
    }

    @font-face {
      font-family: "GT Eesti Pro Display";
      src: url("fonts/GT\ Eesti\ Pro\ Display-Regular.woff2");
      font-style: normal;
      font-weight: 300;
    }

    @font-face {
      font-family: "GT Eesti Pro Display";
      src: url("fonts/GT\ Eesti\ Pro\ Display-Medium.woff2");
      font-style: normal;
      font-weight: 500;
    }

    @font-face {
      font-family: "GT Eesti Pro Display";
      src: url("fonts/GT\ Eesti\ Pro\ Display-Bold.woff2");
      font-style: normal;
      font-weight: 700;
    }

    * {
      font-family: "GT Eesti Pro Display";
      margin: 0;
      padding: 0;
      font-weight: 300;
    }

    h3 {
      font-weight: 300;
    }

    ul {
      list-style: none;
    }

    a {
      text-decoration: none;
    }

    .container {
      padding-left: 115px;
      padding-right: 115px;
      /* max-width: calc(128rem + 40px); */
    }

    @media only screen and (min-width: 320px) {
      .container {
        padding-left: 10px;
        padding-right: 10px;
      }
    }

    @media only screen and (min-width: 375px) {
      .container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    @media only screen and (min-width: 1024px) {
      .container {
        padding-left: 69px;
        padding-right: 69px;
      }
    }

    /* @media (min-width: 2560px) {
      .container {
        padding-left: 215px;
        padding-right: 215px;
      }
    } */
</style>
