<template>
  <div id="info_component">
    <div class="container">
      <div class="row">
        <div
          class="infoimg_container col-4"
          v-for="(info, index) in infoGenerator"
          :key="index"
        >
          <div class="bg-white">
            <HoveredImage
              :path="infoGenerator[index].image + '.jpg'"
              :title="infoGenerator[index].title"
              :subtitle="infoGenerator[index].subtitle"
            ></HoveredImage>
            <div class="info_text">
              <h5 class="mt-3">{{ infoGenerator[index].title }}</h5>
              <p class="date">December 7th,2015</p>
              <div class="line mb-3"></div>
              <p>
                Technology is Here to Stay Lorem ipsum dolor sit amet
                consectetur adipisicing elit. Autem libero hic enim nulla
                voluptatum illo sequi error placeat, eligendi molestiae?
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HoveredImage from "./HoveredImage.vue";
export default {
  components: {
    HoveredImage,
  },
  data() {
    return {
      infoGenerator: [
        {
          image: "blog-post1",
          title: "Redeveloping Florida's Remote Southern Coast",
          subtitle: "Architecturre, Construction, Marketing",
        },
        {
          image: "blog-post2",
          title: "How We Manage Large Construction Projects",
          subtitle: "Architecturre, Construction, Engineering",
        },
        {
          image: "blog-post3",
          title: "Future prooofing a modern home",
          subtitle: "Architecturre, Construction, Marketing",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.container {
  max-width: 980px !important;
}
.bg-white {
  max-width: 300px;

  img {
    width: 300px;
  }
  .info_text {
    padding: 15px;
    .date {
      font-size: 0.8rem;
    }
    .line {
      background-color: #eeeeee;
      height: 1px;
    }
  }
}
</style>