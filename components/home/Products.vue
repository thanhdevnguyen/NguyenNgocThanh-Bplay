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
        <ProductMobile/>
      </div>

    </div>
  </section>
</template>

<script>
import ProductMobile from "./Products-Mobile"

export default {
  name: "Products",
  components: {
    ProductMobile
  }
}
</script>

<style lang="scss" scoped>
.container-product {
  background-image: url(../../assets/images/home/backgroud_our_products.png), url(../../assets/images/home/background_wave.png);
  background-repeat: no-repeat, no-repeat;
  background-size: contain, cover;
  background-position: top, bottom;
  max-width: 100%;
  padding-bottom: 200px;

  .wrapper-title {
    color: #FDFDFD;
    padding: 200px 0 50px 0;

    .container-title {
      .bplay-title {
        font-size: 24px;
        letter-spacing: 10px;
        color: #FF3232;
      }
    }

    .container-content {
      .content {
        font-size: 16px;
        letter-spacing: 1px;
      }
    }
  }

  .wrapper-product {
    .container-item {
      color: #fdfdfd;
      margin-bottom: 30px;

      .container-image {
        img {
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
          font-size: 30px;
          line-height: 35px;
          font-weight: 700;
          margin: 0 auto;
        }
      }

      .sub-title {
        font-size: 16px;
        line-height: 28px;
        letter-spacing: 1px;
        width: 80%;
        text-align: center;
        margin: 0 auto;
        font-weight: 600;
      }
    }

  }
  .wrapper-product-mobile {
    display: none;
  }
}

@media screen and (max-width: 1199px) {
  .container-product {
    .wrapper-product {
      .container-item {
        .sub-title {
          font-size: 14px;
          line-height: 25px;
        }

        .container-title {
          .title {
            font-size: 22px;
            line-height: 23px;
            font-weight: 500;
          }
        }
      }
    }
  }
}

@media screen and (max-width: 767px) {
  .container-product {
    .wrapper-title {
      text-align: center;
      padding: 80px 0 0 0;

      .container-title {
        .bplay-title {
          font-size: 12px;
          letter-spacing: 5px;
          line-height: 14px;
          font-weight: 400;
          padding-bottom: 5px;
        }

        .title {
          font-size: 26px;
          line-height: 30px;
          letter-spacing: 1px;
          font-weight: 800;
        }
      }

      .container-content {
        font-size: 16px;
        line-height: 32px;
        font-weight: 400;
      }
    }

    .wrapper-product {
      display: none;
      .container-item {
        margin-bottom: 20px;

        .sub-title {
          font-size: 14px;
          line-height: 20px;
        }

        .container-title {
          margin: 20px auto 10px auto;

          .title {
            font-size: 20px;
            line-height: 22px;
            font-weight: 500;
          }
        }
      }
    }
    .wrapper-product-mobile {
      display: block;
      padding-top: 40px;
    }
  }
}
</style>
