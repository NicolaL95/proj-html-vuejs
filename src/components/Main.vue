<template>
  <div id="main_container">
    <div class="hero_image position-relative">
      <img src="../assets/home-slider.jpg" alt="Avada Construction logo" />
      <div class="hero_title position-absolute">
        <h1 class="pb-2">BUILDING INSPIRIING SPACES</h1>
        <p class="pb-2">
          We Build Inspiring Residential &#38; Commercial Spaces
        </p>
        <div class="title_button d-flex justify-content-center">
          <button class="bw_button border-0 button_size">
            EXPLORE RECENT WORK
          </button>
          <button class="quote_button border-0 button_size">
            GET A QUOTE TODAY
          </button>
        </div>
      </div>
    </div>
    <div class="project_help position-relative">
      <p>Do You Have a Construction Project We Can Help With?</p>
      <div class="white_b d-inline-block position-absolute fq_b">
        <button class="bw_button free_quote">GET A FREE QUOTE</button>
      </div>
    </div>
    <div class="info_desc">
      <div class="container inf_size">
        <h3 class="lg_text">Specialist in Modern Construction</h3>
        <div class="by mt-3 mb-3"></div>
        <p class="lg_text">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt at
          unde, atque consequuntur adipisci corporis eum dolorem blanditiis
          maxime!
        </p>
      </div>
    </div>
    <Card />

    <div class="company_stat position-relative mt-5">
      <div class="position-absolute img_rounder ir_t"></div>
      <div class="abs_center position-absolute">
        <CompInfo />
      </div>
      <img src="../assets/home.jpg" alt="Working Table" />
      <div class="position-absolute img_rounder ir_b"></div>
    </div>
    <div class="info_desc">
      <div class="container inf_size">
        <h3 class="lg_text">Explore Recent Work</h3>
        <div class="by mt-3 mb-3"></div>
        <p class="lg_text">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt at
          unde, atque consequuntur adipisci corporis eum dolorem blanditiis
          maxime!
        </p>
      </div>
    </div>
    <div class="img_container container">
      <div class="row">
        <div class="col-4 position-relative">
          <div class="bg_gold">
            <img
              class="w-100 img_size"
              src="../assets/project1.jpg"
              alt="Home image"
            />
            <div class="backdrop_image abs_center position-absolute w-100">
              <div class="icons_hovered">
                <i class="fas fa-link rounded-circle"></i>
                <i class="fas fa-search rounded-circle"></i>
                <h5>Florida Heath Facility</h5>
                <p>Commerial</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4 position-relative">
          <div class="bg_gold">
            <img
              class="w-100 img_size"
              src="../assets/project2.jpg"
              alt="Home image"
            />
            <div class="backdrop_image abs_center position-absolute w-100">
              <div class="icons_hovered">
                <i class="fas fa-link rounded-circle"></i>
                <i class="fas fa-search rounded-circle"></i>
                <h5>Florida Heath Facility</h5>
                <p>Commerial</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4">
          <img
            class="w-100 img_size"
            src="../assets/project3.jpg"
            alt="Home image"
          />
        </div>
      </div>
    </div>
    <div class="view_prog container mt-4 mb-5">
      <div class="row align-items-center justify-content-center p_lr">
        <div class="line col-4"></div>
        <p class="col-4 m-0 text-center">VIEW ALL PROJECT</p>
        <div class="line col-4"></div>
      </div>
    </div>
    <div class="bg_g">
      <div class="info_desc">
        <div class="container inf_size">
          <h3 class="lg_text">Our Core Values</h3>
          <div class="by mt-3 mb-3"></div>
          <p class="lg_text">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt
            at unde, atque consequuntur adipisci corporis eum dolorem blanditiis
            maxime!
          </p>
        </div>
      </div>
      <div class="comp_qualities">
        <div class="container">
          <div class="row">
            <div class="col-3 text-center">
              <i class="fas fa-home bg_a qualities_size mb-3"></i>
              <h5>Great Services</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque eius perspiciatis eligendi blanditiis id
                repellendus. A minima tempore tenetur!
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="fas fa-cog bg_b qualities_size mb-3"></i>
              <h5>Great Services</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque eius perspiciatis eligendi blanditiis id
                repellendus. A minima tempore tenetur!
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="fas fa-users bg_o qualities_size mb-3"></i>
              <h5>Great Services</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque eius perspiciatis eligendi blanditiis id
                repellendus. A minima tempore tenetur!
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="far fa-lightbulb bg_g qualities_size mb-3"></i>
              <h5>Great Services</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque eius perspiciatis eligendi blanditiis id
                repellendus. A minima tempore tenetur!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="owners_stat position-relative mt-5">
        <div class="position-absolute img_rounder_g ir_t"></div>
        <div class="abs_center position-absolute testimonial_container">
          <h3>Our Home Owners Say</h3>
          <div class="by"></div>
          <img
            class="rounded-circle testimonial_img my-4"
            src="../assets/testimonial.jpg"
            alt="testiimonial Image"
          />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae
            mollitia pariatur, corporis molestiae quia, quis voluptatibus
            exercitationem quidem sapiente perferendis praesentium optio? Odio
            consequuntur laborum alias minus. Cum blanditiis facilis esse
            exercitationem! Quis, velit consequuntur?
          </p>
          <h5>HARRY SMITH - NEW HOEM OWNERS</h5>
          <div class="testimonial_switch">
            <i class="fas fa-circle"></i>
            <i class="far fa-circle"></i>
          </div>
        </div>
        <img src="../assets/home-parallax.jpg" alt="Working Table" />
        <div class="position-absolute img_rounder_g ir_b"></div>
      </div>
      <div class="info_desc">
        <div class="container inf_size">
          <h3 class="lg_text">Lastest News</h3>
          <div class="by mt-3 mb-3"></div>
          <p class="lg_text">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt
            at unde, atque consequuntur adipisci corporis eum dolorem blanditiis
            maxime!
          </p>
        </div>
      </div>
      <ImgInformation />
      <div class="view_prog container mt-4 mb-5">
        <div class="row align-items-center justify-content-center p_lr">
          <div class="line col-4 border-white"></div>
          <p class="col-4 m-0 text-center">VIEW ALL PROJECT</p>
          <div class="line col-4 border-white"></div>
        </div>
      </div>
    </div>
    <div class="info_desc">
      <div class="container inf_size">
        <h3 class="lg_text">Trusted Partners</h3>
        <div class="by mt-3 mb-3"></div>
        <p class="lg_text">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt at
          unde, atque consequuntur adipisci corporis eum dolorem blanditiis
          maxime!
        </p>
      </div>
    </div>
    <Partners></Partners>
    <div class="CTA position-relative">
      <img src="../assets/CTA.jpg" alt="Construction progress" />
      <div class="position-absolute abs_center">
        <div class="row align-items-center">
          <div class="col-8">
            <div class="info_desc text_left">
              <div class="">
                <h3 class="lg_text text-white">Trusted Partners</h3>
                <div class="by my-3 mx-0"></div>
                <p class="lg_text text-white">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse
                  sunt at unde, atque consequuntur adipisci corporis eum dolorem
                  blanditiis maxime!
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 text-white">
            <button class="quote_button border-0 button_size">
              GET A FREE QUOTE
            </button>
            <p class="minus_text">Only takes a few seconds!</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";
import CompInfo from "./CompInfo.vue";
import ImgInformation from "./ImgInformation.vue";
import Partners from "./Partners.vue";
export default {
  components: {
    Card,
    CompInfo,
    ImgInformation,
    Partners,
  },
  data() {
    return {};
  },
};
</script>

<style lang="scss">
#main_container {
  .hero_image {
    img {
      height: 700px;
      width: 100%;
    }

    .hero_title {
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;

      h1 {
        color: white;
        font-size: 3rem;
      }

      p {
        color: #fed23f;
        font-size: 1.2rem;
      }

      .title_button {
        gap: 20px;
      }
    }
  }

  .project_help {
    background-color: #fed23f;
    text-align: center;

    p {
      padding: 30px;
      font-size: 1.5rem;
      color: #1e1e1e;
    }
    .fq_b {
      top: 50%;
      left: 50%;
      transform: translate(-50%, 75%);
    }
    .free_quote {
      border: 1px solid black;
      padding: 5px 20px;
    }
  }
  .info_desc {
    padding: 75px 0 50px 0;

    .inf_size {
      width: 33%;
      text-align: center;
    }
  }
  .company_stat {
    .img_rounder {
      height: 100px;
      background-color: white;
      border-radius: 25%;

      margin: 0;
      padding: 0;
      width: 100%;
    }
    .ir_t {
      top: -30px;
    }
    .ir_b {
      bottom: -30px;
    }
    img {
      height: 600px;
      width: 100%;
    }
  }

  /* images */

  .img_size {
    height: 300px;
  }
  /* VAP  */
  .p_lr {
    padding: 0 12px;
    .line {
      border: 1px solid #6b6868;
      height: 1px;
    }
  }
  .owners_stat {
    .abs_center {
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    .img_rounder_g {
      height: 100px;
      background-color: lightgrey;
      border-radius: 25%;

      margin: 0;
      padding: 0;
      width: 100%;
    }
    .ir_t {
      top: -30px;
    }
    .ir_b {
      bottom: -30px;
    }
    img {
      height: 600px;
      width: 100%;
    }
  }
  .comp_qualities {
    .container {
      .row {
        .qualities_size {
          font-size: 2.5rem;
          border-radius: 50%;
          padding: 15px;
          color: white;
        }

        .bg_a {
          background-color: #8faeb8;
        }

        .bg_b {
          background-color: #6586b1;
        }

        .bg_o {
          background-color: #fe6f1d;
        }

        .bg_g {
          background-color: #7d9703;
        }
        .bb {
          background-color: #31312f;
          height: 2px;
          width: 20px;
          margin: auto;
          border-radius: 5px;
        }
      }
    }
  }

  /* TESTIMONIAL */
  .testimonial_container {
    color: white;
    .testimonial_img {
      height: 130px !important;
      width: 115px !important;
    }
    h5 {
      font-weight: bold;
    }
    .testimonial_switch {
      font-size: 0.8rem;
      i:first-child {
        padding-right: 5px;
      }
    }
  }

  /* CALL TO ACTION */
  .CTA {
    background-color: #31312f;
    padding-bottom: 10px;
    img {
      height: 600px;
      width: 100%;
    }
  }

  /* REUSED COMPONENTS */
  .by {
    border: 1px solid #fed23f;
    width: 250px;
    margin: auto;
  }

  /* UTILITY_MAIN */
  .white_b {
    border: 1px solid white;
  }
  .bg_g {
    background-color: lightgray;
  }
  .text_left {
    text-align: left;
  }

  /* HOVER */
  .bg_gold {
    background-color: #fed23f;
  }
  .backdrop_image {
    visibility: hidden;
    .icons_hovered {
      i {
        color: #fed23f;
        padding: 10px;
        background-color: white;
        margin-left: 12px;
      }
    }
    p,
    h5 {
      color: white;
    }
  }
  .img_container:hover img {
    visibility: hidden;
  }
  .img_container:hover .backdrop_image {
    visibility: visible;
  }
}
</style>