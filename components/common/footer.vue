<template>
  <footer class="container-footer">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 wow fadeInLeft">
          <div class="logo-footer">
            <a href="/">
              <img src="~/assets/images/header/logo.svg"/>
            </a>
          </div>
        </div>
        <div id="contact" class="col-lg-6 wow fadeInRight">
          <div class="container-contact-us">
            <p class="title">CONTACT US</p>
            <div class="container-content">
              <div class="content row">
                <div class="icon">
                  <img src="~/assets/images/footer/icon-location.svg"/>
                </div>
                <div class="info">
                  <a>2901 Marmora Road, Glassgow, Seattle, WA 98122-1090</a>
                </div>
              </div>
              <div class="content row">
                <div class="icon">
                  <img src="~/assets/images/footer/icon-email.svg"/>
                </div>
                <div class="info">
                  <a href="mailto:info@bplay.uk">info@bplay.uk</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container-footer-bottom">
        <div class="row footer-bottom">
          <div class="col-lg-6 col-md-6">
            <div class="container-logo row desktop">
              <div class="col-6 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-1.png"/>
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-2.png"/>
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-3.png"/>
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer4.png"/>
                </a>
              </div>
            </div>
            <div class="container-logo row mobile">
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/mobile-footer-1.png"/>
                </a>
              </div>
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-3.png"/>
                </a>
              </div>
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/footer4.png"/>
                </a>
              </div>
              <div class="col-12 text-center custom-last-item">
                <a>
                  <img src="~/assets/images/footer/footer-1.png"/>
                </a>
              </div>
            </div>
          </div>
          <div class="col-lg-6 col-md-6">
            <div class="copyright text-center">
              <p class="text">
                Copyright © 2020 bplay.com. All rights reserved.
              </p>
            </div>
            <div
              @click="moveTop"
              class="container-move-top"
              :class="isScroll ? 'show' : ''"
            >
              <img
                alt=""
                class="imgAuto"
                src="~/assets/images/footer/arrow-scroll-top.svg"
              />
              <p>Top</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      isScroll: false
    }
  },
  mounted() {
    window.addEventListener("scroll", this.onScroll)
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.onScroll)
  },
  methods: {
    onScroll(e) {
      const currentScrollPosition = window.pageYOffset || document.documentElement.scrollTop
      this.isScroll = currentScrollPosition > 0;
    },
    moveTop() {
      window.scroll({
        top: 0,
        left: 0,
        behavior: 'smooth'
      })
    }
  }
};
</script>

<style lang="scss" src="assets/scss/partial/_footer.scss"/>
