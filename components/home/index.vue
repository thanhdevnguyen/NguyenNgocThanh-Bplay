<template>
  <div class="wrapper-home">
    <Banner/>
    <About/>
    <Products/>
    <Partner/>
    <Clients/>
  </div>
</template>

<script>
if (process.browser) {
  var {WOW} = require('wowjs')
}
import Products from "./Products";
import Banner from "./Banner";
import About from "./About";
import Partner from "./Partner";
import Clients from "./Clients";

export default {
  components: {
    Products,
    Banner,
    About,
    Partner,
    Clients
  },
  mounted() {
    this.$nextTick(() => {
      if (process.browser) {
        new WOW({animateClass: 'animate__animated'}).init()
      }
    });
  },
}
</script>

<style lang="scss" src="assets/scss/partial/_home.scss"/>
