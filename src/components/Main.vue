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
        <div class="col-4">
          <img
            class="w-100 img_size"
            src="../assets/project1.jpg"
            alt="Home image"
          />
        </div>
        <div class="col-4">
          <img
            class="w-100 img_size"
            src="../assets/project2.jpg"
            alt="Home image"
          />
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
      <div class="owners_stat position-relative mt-5">
        <div class="position-absolute img_rounder_g ir_t"></div>
        <div class="abs_center position-absolute"></div>
        <img src="../assets/home-parallax.jpg" alt="Working Table" />
        <div class="position-absolute img_rounder_g ir_b"></div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";
import CompInfo from "./CompInfo.vue";
export default {
  components: {
    Card,
    CompInfo,
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
    .by {
      border: 1px solid #fed23f;
      width: 250px;
      margin: auto;
    }
    .inf_size {
      width: 33%;
      text-align: center;
    }
  }
  .company_stat {
    .abs_center {
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
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
  /* UTILITY_MAIN */
  .white_b {
    border: 1px solid white;
  }
  .bg_g {
    background-color: lightgray;
  }
}
</style>