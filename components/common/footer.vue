<template>
  <footer class="container-footer">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="logo-footer">
            <a href="/">
              <img src="~/assets/images/header/logo.svg"/>
            </a>
          </div>
        </div>
        <div id="contact" class="col-lg-6">
          <div class="container-contact-us">
            <p class="title">CONTACT US</p>
            <div class="container-content">
              <div class="content row">
                <div class="icon">
                  <img src="~/assets/images/footer/icon-location.svg" />
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
                  <img src="~/assets/images/footer/footer-1.png" />
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-2.png" />
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-3.png"/>
                </a>
              </div>
              <div class="col-2 text-center">
                <a>
                  <img src="~/assets/images/footer/footer4.png" />
                </a>
              </div>
            </div>
            <div class="container-logo row mobile">
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/mobile-footer-1.png" />
                </a>
              </div>
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/footer-3.png"/>
                </a>
              </div>
              <div class="col-4 text-center">
                <a>
                  <img src="~/assets/images/footer/footer4.png" />
                </a>
              </div>
              <div class="col-12 text-center custom-last-item">
                <a>
                  <img src="~/assets/images/footer/footer-1.png" />
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
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.container-footer {
  background-color: #15161e;
  background-image: url(../../assets/images/footer/mask_group.png);
  background-repeat: no-repeat;
  background-size: cover;
  padding: 370px 0 40px 0;
  .container-contact-us {
    color: #FDFDFD;
    .title {
      font-size: 34px;
      font-weight: 800;
      line-height: 40px;
    }
    .container-content {
      font-size: 28px;
      line-height: 40px;
      font-weight: 400;
      .content {
        padding: 5px 0;
        .icon {
          width: 10%;
        }
        .info {
          width: 90%;
          a {
            color: #FDFDFD;
          }
        }
      }
    }
  }
  .container-footer-bottom {
    margin-top: 50px;
    border-top: 0.5px solid #424657;
    .footer-bottom {
      padding-top: 30px;
      .mobile {
        display: none;
      }
    }
  }
  .copyright {
    font-size: 14px;
    font-weight: 400;
    line-height: 28px;
    color: #FDFDFD;
    float: right;
  }
}
@media screen and (max-width: 767px) {
  .container-footer {
    padding: 300px 0 0 0;
    .logo-footer {
      margin-bottom: 20px;
      max-width: 140px;
    }
    .container-contact-us {
      .title {
        font-size: 18px;
        line-height: 21px;
        font-weight: 800;
      }
      .container-content {
        font-size: 16px;
        line-height: 23px;
        font-weight: 400;
        .content {
          margin-left: 0;
        }
      }
    }
    .container-footer-bottom {
      border-top: 0.5px solid #222330;
      .footer-bottom {
        padding-top: 10px;
        .custom-last-item {
          margin-top: 10px;
        }
        .desktop {
          display: none;
        }
        .mobile {
          display: flex;
          padding: 20px 0;
        }
      }
    }
    .copyright {
      border-top: 0.5px solid #222330;
      float: unset;
      padding: 10px 0 0 0;
      font-size: 13px;
      line-height: 28px;
      font-weight: 400;
      letter-spacing: 2px;
    }
  }
}
</style>
