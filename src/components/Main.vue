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
          <button class="bw_button border-0 button_size button_size_b">
            EXPLORE RECENT WORK
          </button>
          <button class="quote_button border-0 button_size button_size_b">
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
    <InfoBox :title="'Specialist in Modern Construction'"></InfoBox>
    <Card />

    <div class="company_stat position-relative mt-5">
      <div class="position-absolute img_rounder ir_t"></div>
      <div class="abs_center position-absolute">
        <CompInfo />
      </div>
      <img src="../assets/home.jpg" alt="Working Table" />
      <div class="position-absolute img_rounder ir_b"></div>
    </div>
    <InfoBox :title="'Explore Recent Work'"></InfoBox>
    <div class="img_container container">
      <div class="row">
        <div class="col-4">
          <HoveredImage
            :path="'project1.jpg'"
            :title="'Florida Heath Facility'"
            :subtitle="'Commercial'"
          ></HoveredImage>
        </div>
        <div class="col-4">
          <HoveredImage
            :path="'project2.jpg'"
            :title="'Maine Modernity'"
            :subtitle="'Residential'"
          ></HoveredImage>
        </div>
        <div class="col-4">
          <HoveredImage
            :path="'project3.jpg'"
            :title="'Exclusive Urban Living'"
            :subtitle="'Commercial'"
          ></HoveredImage>
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
      <InfoBox :title="'Our Core Values'"></InfoBox>
      <div class="comp_qualities">
        <div class="container">
          <div class="row">
            <div class="col-3 text-center">
              <i class="fas fa-home bg_a qualities_size mb-3"></i>
              <h5 class="qualities_title">Great Services</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque.
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="fas fa-cog bg_b qualities_size mb-3"></i>
              <h5 class="qualities_title">Highest Standards</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque.
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="fas fa-users bg_o qualities_size mb-3"></i>
              <h5 class="qualities_title">Professional Team</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque.
              </p>
            </div>
            <div class="col-3 text-center">
              <i class="far fa-lightbulb bg_g qualities_size mb-3"></i>
              <h5 class="qualities_title">Creative Solutions</h5>
              <div class="bb mt-3 mb-4"></div>
              <p>
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                Dolorum eaque.
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
          <h5>HARRY SMITH - NEW HOME OWNERS</h5>
          <div class="testimonial_switch">
            <i class="fas fa-circle"></i>
            <i class="far fa-circle"></i>
          </div>
        </div>
        <img src="../assets/home-parallax.jpg" alt="Working Table" />
        <div class="position-absolute img_rounder_g ir_b"></div>
      </div>
      <InfoBox :title="'Lastest News'"></InfoBox>
      <ImgInformation />
      <div class="view_prog container mt-4 mb-5">
        <div class="row align-items-center justify-content-center p_lr">
          <div class="line col-4 border-white"></div>
          <p class="col-4 m-0 text-center">VIEW ALL ARTICLES</p>
          <div class="line col-4 border-white"></div>
        </div>
      </div>
    </div>
    <InfoBox :title="'Trusted Partners'"></InfoBox>
    <Partners></Partners>
    <div class="CTA position-relative">
      <img src="../assets/CTA.jpg" alt="Construction progress" />
      <div class="position-absolute abs_center">
        <div class="row align-items-center">
          <div class="col-8">
            <div class="info_desc text_left">
              <div class="">
                <h3 class="lg_text text-white text_b">Trusted Partners</h3>
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
            <button class="quote_button border-0 button_size button_size_b">
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
import InfoBox from "./InfoBox.vue";
import HoveredImage from "./HoveredImage.vue";
export default {
  components: {
    Card,
    CompInfo,
    ImgInformation,
    Partners,
    InfoBox,
    HoveredImage,
  },
  data() {
    return {};
  },
};
</script>

<style lang="scss">
#main_container {
  .hero_image {
    padding-top: 115px;
    img {
      height: 900px;
      width: 100%;
    }

    .hero_title {
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;

      h1 {
        color: white;
        font-size: 3.5rem;
      }

      p {
        color: #fed23f;
        font-size: 1.5rem;
      }

      .title_button {
        gap: 20px;
      }
    }
  }
  /* PROJECT_HELP */
  .project_help {
    background-color: #fed23f;
    text-align: center;

    p {
      padding: 40px;
      font-size: 2rem;
      color: #1e1e1e;
    }
    .fq_b {
      top: 50%;
      left: 50%;
      transform: translate(-50%, 120%);
    }
    .free_quote {
      border: 1px solid black;
      padding: 5px 20px;
    }
  }
  .info_desc {
    padding: 75px 0 50px 0;
  }

  /* COMPANY_STAT */
  .company_stat {
    .img_rounder {
      height: 200px;
      background-color: white;
      border-radius: 25%;

      margin: 0;
      padding: 0;
      width: 100%;
    }
    .ir_t {
      top: -50px;
    }
    .ir_b {
      bottom: -50px;
    }
    img {
      height: 800px;
      width: 100%;
    }
  }

  /* IMAGES */

  .img_size {
    height: 300px;
  }
  /* VAP  */
  .p_lr_b {
    margin-bottom: 0;
    padding-bottom: 120px;
  }
  .p_lr {
    padding: 0 12px;
    margin-top: 100px;
    margin-bottom: 120px;

    .line {
      border: 1px solid #eeeeee;
      height: 1px;
    }
  }
  /* OWNERS_STAT */
  .owners_stat {
    .abs_center {
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    .img_rounder_g {
      height: 200px;
      background-color: #eeeeee;
      border-radius: 25%;

      margin: 0;
      padding: 0;
      width: 100%;
    }
    .ir_t {
      top: -50px;
    }
    .ir_b {
      bottom: -50px;
    }
    img {
      height: 800px;
      width: 100%;
    }
  }

  /* COMP_QUALITIES */
  .comp_qualities {
    .container {
      .row {
        .qualities_size {
          font-size: 4rem;
          border-radius: 50%;
          color: white;
          width: 120px;
          height: 120px;
          line-height: 120px;
        }

        .bg_a {
          background-color: #8faeb8;
        }

        .qualities_size:hover {
          background-color: #fed23f;
        }
        .qualities_size:hover + .qualities_title {
          color: #fed23f;
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
        padding-right: 10px;
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
    background-color: #eeeeee;
    padding-bottom: 10px;
  }
  .text_left {
    text-align: left;
  }

  /* HOVER */
}
</style>