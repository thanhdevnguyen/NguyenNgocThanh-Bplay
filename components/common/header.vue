<template>
  <header class="wrapper-header" :class="isScroll ? 'fixed' : ''">
    <div class="container flex-box justify-between align-center">
      <h1 class="container-logo">
        <a>
          <img src="~/assets/images/header/logo.svg"/>
        </a>
      </h1>
      <nav class="container-menus fixed" :class="showTopMenu ? 'mobile' : '' ">
        <a class="btn-close" @click="showTopMenu = !showTopMenu">
          <img src="~/assets/images/header/close.svg"/>
        </a>
        <ul class="menus flex-box" @click="showTopMenu = !showTopMenu">
          <li @click="activate(1)" :class="{ active : activeNumber === 1 }">
            <a href="#about">ABOUT US</a>
          </li>
          <li @click="activate(2)" :class="{ active : activeNumber === 2 }">
            <a href="#product">PRODUCTS</a>
          </li>
          <li @click="activate(3)" :class="{ active : activeNumber === 3 }">
            <a href="#partner">OUR PARTNERS</a>
          </li>
          <li @click="activate(4)" :class="{ active : activeNumber === 4 }">
            <a href="#clients">OUR CLIENTS</a>
          </li>
          <li @click="activate(5)" :class="{ active : activeNumber === 5 }">
            <a href="#contact">CONTACT US</a>
          </li>
        </ul>
        <div class="language language-mobile">
          <ul class="unstyled">
            <li class="current">
              <a href="#" class="current-lang">
                <img src="~/assets/images/header/flag-eng.svg"/>
                <span>ENG</span>
              </a>
            </li>
          </ul>
        </div>
      </nav>
      <div class="language">
        <ul class="unstyled">
          <li class="current">
            <a href="#" class="current-lang">
              <img src="~/assets/images/header/flag-eng.svg"/>
              <span>ENG</span>
            </a>
          </li>
        </ul>
      </div>
      <div class="btnNav" @click="showTopMenu = !showTopMenu">
        <img src="~/assets/images/header/bar.svg"/>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      showTopMenu: false,
      isScroll: false,
      activeNumber: 0
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
    activate(el) {
      this.activeNumber = el;
    }
  },
};
</script>

<style lang="scss" src="assets/scss/partial/_header.scss"/>
