<template>
  <section id="product" class="container-product">
    <div class="container">
      <div class="row wrapper-title">
        <div class="col-lg-4">
          <div class="container-title wow fadeInLeft">
            <div class="bplay-title">BPLAY GAME</div>
            <h2 class="title">OUR PRODUCTS</h2>
          </div>
        </div>
        <div class="col-lg-8">
          <div class="container-content wow fadeInRight">
            <p class="content">BPlay’s high quality iGaming Platform offers a complete solution for your casino.
              Get the full White Label turnkey solution or the Seamless API with our comprehensive selection of games.
              Through our global network of premium partners such as Vivo Gaming, SBTech and HoGaming you will have
              access to the best Live Casino,
              Sportsbook, Slots, Table Games, Number Games and Fishing Games on the market.</p>
          </div>
        </div>
      </div>
      <div class="wrapper-product container wow bounceInUp">
        <div class="row">
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
        </div>
      </div>
      <div class="wrapper-product-mobile">
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
    </div>
  </section>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: "Products",
  components: {
    VueSlickCarousel
  },
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

<style lang="scss" src="assets/scss/partial/_product.scss"/>
