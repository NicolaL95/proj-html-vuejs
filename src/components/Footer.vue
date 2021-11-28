<template>
  <div id="footer_container">
    <div class="container mw_17">
      <div class="row">
        <div class="col-3">
          <img
            class="logo_foooter"
            src="../assets/footer-logo.png"
            alt="Logo"
          />
          <p class="lh_21">
            We are specialists in the construction of unique and exclusive
            properties. Our Work inspires. We pride ourselves on delivering
            outstanding quality and design for leading clients accross the
            world.
          </p>
          <button class="quote_button border-0 button_size">LEARN MORE</button>
        </div>
        <div class="col-3">
          <h6 class="titles_footer">LASTEST TWEETS</h6>
          <div class="twitter_container d-flex position-relative">
            <img
              class="position-absolute icon_w icon_p_a"
              src="../assets/twitter_image.svg"
              alt="twitter icon"
            />
            <div class="twitter_logo_container">
              <img
                class="rounded-circle logo_size"
                src="../assets/logo_twit.png"
                alt="Logo"
              />
            </div>
            <div class="twitter_text mb-3">
              <h6 class="twitter_nickname font-weight-bold">ThemeFusion</h6>
              <p class="twitter_id">@Theme_fusion</p>
              <p>
                Do you need sublime WordPress hosting for your next website?
                Take advantage of exclusive partner offers that we have securred
                just for you, &#09; launch your site in seconds with
                <span class="text-primary">#avada</span> on WP Engine hosting
                &#09; get 30% Off this Black Friday
                <span class="text-primary"
                  >bit.ly/3kjLLE2 #BlackFriday2020</span
                >
              </p>
            </div>
          </div>
          <img class="w-100 wp_engine" src="../assets/promo.jpeg" alt="" />
          <div class="icon_share d-flex justify-content-between mt-2">
            <div class="icon">
              <img class="icon_w" src="../assets/like_image.svg" alt="Like" />
              <img
                class="icon_w mx-3"
                src="../assets/link_image.svg"
                alt="Link"
              />
            </div>
            <div class="date">
              <p>22h</p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <h6 class="titles_footer">CONTACT US TODAY</h6>
          <div class="contacts d-flex">
            <i class="fas fa-globe"></i>
            <p>
              Corporrate Location <br />
              1600 Amphitheatre Parkway <br />
              London WC11BA
            </p>
          </div>
          <div class="contacts d-flex">
            <i class="fas fa-home"></i>
            <p>
              REsidential Location <br />
              9521 Broadsberry Avenue <br />
              Paddington RC7 9ZA
            </p>
          </div>
          <div class="contacts d-flex">
            <i class="fas fa-phone"></i>
            <p>1.800.458.556 / 1.800.532.2112</p>
          </div>
          <div class="contacts d-flex">
            <i class="far fa-envelope"></i>
            <p>info@your-domain.com</p>
          </div>
          <div class="contacts d-flex">
            <i class="far fa-clock"></i>
            <p>Monday-Friday: 9:00 AM - 6:00 PM</p>
          </div>
          <div class="contacts d-flex">
            <i class="far fa-clock"></i>
            <p>Saturday-Sunday: 9:00 AM - 12:00 PM</p>
          </div>
        </div>
        <div class="col-3">
          <h6 class="titles_footer">FIND US</h6>
          <img
            class="w-100"
            src="../assets/construction_map_pin.png"
            alt="Map"
          />
        </div>
      </div>
    </div>
    <div class="copyright d-flex justify-content-between">
      <p>
        COPYRIGHT 2012 - 2015 VADA THEME BY
        <span class="text-secondary font_bold">THEME FUSION</span> | ALL RIGHT
        RESERVED | POWERED BY
        <span class="text-secondary font_bold">WORDPRESS</span>
      </p>
      <div class="icon_footer d-flex">
        <i class="fab fa-facebook-f"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-youtube"></i>
        <i class="fab fa-instagram"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#footer_container {
  background-color: #1e1e1e;
  color: #6b6868;
  .row {
    padding: 60px;

    .col-3 {
      .lh_21 {
        line-height: 2.1;
      }
      .titles_footer {
        color: #fed23f;
      }
      .logo_footer {
        padding: 30px 0;
      }
      .logo_size {
        width: 35px;
        margin-right: 10px;
      }
      .wp_engine {
        height: 290px;
        padding-left: 45px;
      }
      .icon_w {
        width: 25px;
      }
      .icon_p_a {
        top: 0;
        right: 0;
      }
      .icon_share {
        margin-left: 45px;
      }
      .contacts {
        gap: 10px;
      }
    }
  }
  .copyright {
    background-color: black;
    padding: 30px 50px;
    p {
      margin: 0;
    }
    .font_bold {
      font-weight: bold;
    }
    .icon_footer {
      gap: 20px;
    }
  }
}
.twitter_text {
  width: calc(100% - 48px);
  color: white;
  p,
  .twitter_nickname {
    margin: 0;
  }
  .twitter_id {
    font-weight: 100;
  }
}
</style>