<template>
  <div>
    <VueSlickCarousel v-bind="settings">
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Live Casino</p>
          </div>
          <div class="sub-title">
            <p>Vivo LiveCasino, HoGaming Live Casino, BPlay LiveCasino</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product8/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Fishing Game</p>
          </div>
          <div class="sub-title">
            <p>BPlay Fishing 2D, BPlay Fishing 3D</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product2/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Sport Book</p>
          </div>
          <div class="sub-title">
            <p>BTI Sportsbook, BPlay Sportsbook</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product3/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Quick Number</p>
          </div>
          <div class="sub-title">
            <p>Keno, Number Games, Lottery</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product4/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">White Label</p>
          </div>
          <div class="sub-title">
            <p>Bplay White Label</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product5/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Slots</p>
          </div>
          <div class="sub-title">
            <p>BPlay Slots, Jackpot Slots</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product6/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Seamless API</p>
          </div>
          <div class="sub-title">
            <p>Seamless API</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product7/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Full Package</p>
          </div>
          <div class="sub-title">
            <p>Full Package</p>
          </div>
        </a>
      </div>
      <div class="container-item col-lg-4 col-md-6">
        <a>
          <div class="container-image">
            <img src="~/assets/images/products/Product2/Rectangle_49.png">
          </div>
          <div class="container-title">
            <p class="title">Table Game</p>
          </div>
          <div class="sub-title">
            <p>Table Game</p>
          </div>
        </a>
      </div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  components: { VueSlickCarousel },
  data() {
    return {
      settings: {
        arrows: false,
        dots: true,
        dotsClass: "slick-dots custom-dot-class",
        autoplay: true,
        autoplaySpeed: 1800
      },
    }
  },
}
</script>

<style lang="scss">
.slick-dots {
  li {
    button {
      width: 12px;
      height: 12px;
      background: #505153;
      -webkit-transform: rotate(45deg);
      -ms-transform: rotate(45deg);
      transform: rotate(45deg);

      &:before {
        font-size: 0;
      }
    }
  }

  .slick-active {
    button {
      background-color: #F41616;
    }
  }
}
.container-item {
  color: #FDFDFD;
  .container-image {
    img {
      margin: 0 auto;
      border-radius: 20px;
    }
  }
  .container-title {
    background-image: url(../../assets/images/home/bg-product.png);
    background-repeat: no-repeat;
    background-size: contain;
    padding: 10px 0;
    background-position: 50%;
    width: 80%;
    margin: 25px auto 15px auto;
    .title {
      text-align: center;
      font-size: 16px;
      line-height: 18px;
      font-weight: 700;
      margin: 0 auto;
    }
  }
  .sub-title {
    font-size: 14px;
    line-height: 26px;
    letter-spacing: 1px;
    width: 80%;
    text-align: center;
    margin: 0 auto;
    font-weight: 600;
  }
}
</style>
