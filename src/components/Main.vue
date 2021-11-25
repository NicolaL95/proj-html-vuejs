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
      <button class="bw_button">GET A FREE QUOTE</button>
    </div>
  </div>
</template>

<script>
export default {};
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
        .bw_button {
          color: white;
          background-color: #6b6868;
        }
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
  }
}
</style>