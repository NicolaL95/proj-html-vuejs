<template>
  <div id="info_component">
    <div class="container">
      <div class="row">
        <div
          class="col-3 info_container"
          v-for="(info, index) in infoGenerator"
          :key="index"
        >
          <i :class="infoGenerator[index].icon"></i>
          <p class="info_color info_i_size">
            {{ infoGenerator[index].number }}
          </p>
          <p class="mt-2 info_title">{{ infoGenerator[index].name }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      infoGenerator: [
        {
          icon: "fas fa-suitcase info_i_size info_color",
          number: 3534,
          name: "PLANNING APPLIATIONS",
        },
        {
          icon: "far fa-building info_i_size info_color",
          number: 896,
          name: "COMPLETED PROJECTS",
        },

        {
          icon: "fas fa-users info_i_size info_color",
          number: 172,
          name: "TRAINED PROFESSIONAL",
        },
        {
          icon: "fas fa-globe info_i_size info_color",
          number: 19,
          name: "INTERNATIONAL OFFICES",
        },
      ],
    };
  },
};
</script>
<style lang="scss">
.info_container {
  .info_i_size {
    font-size: 3rem;
  }
  .info_color {
    color: #fed23f;
  }
  .info_title {
    color: white;
    font-size: 0.8rem;
    width: 100%;
  }
}
</style>