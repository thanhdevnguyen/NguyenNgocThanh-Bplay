<template>
  <section id="about" class="container-about">
    <div class="container">
      <div class="container-title text-center wow bounceInUp">
        <div class="bplay-title">BPLAY GAME</div>
        <p class="title">WHO WE ARE?</p>
        <p class="content">BPlay was founded in 2015 by a group of highly skilled professionals with over 15 years of
          experience in the iGaming industry.
          Today we are an international company with more than 100 employees and have operations in Malta, Ukraine,
          Romania, Norway, India, Myanmar and Taiwan...</p>
      </div>
    </div>

    <div class="container-maps text-center wow zoomIn">
      <img class="maps" src="~/assets/images/about/maps.png">
      <div class="content-year wow fadeInLeft">
      </div>
    </div>
    <div class="container-buildings">
      <div class="buildings">
        <img src="~/assets/images/about/buildings.png">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
}
</script>

<style lang="scss" src="assets/scss/partial/_about.scss"/>
