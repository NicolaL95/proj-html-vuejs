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
  </div>
</template>

<script>
import Card from "./Card.vue";
export default {
  components: {
    Card,
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
      height: 800px;
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
}

/* UTILITY_MAIN */
.white_b {
  border: 1px solid white;
}
</style>