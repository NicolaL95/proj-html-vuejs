<template>
  <div class="bg_gold position-relative">
    <img
      class="w-100 img_size"
      :src="require('../assets/' + path)"
      alt="Home image"
    />
    <div class="backdrop_image abs_center position-absolute w-100">
      <div class="icons_hovered">
        <i class="fas fa-link rounded-circle"></i>
        <i class="fas fa-search rounded-circle"></i>
        <h5>{{ title }}</h5>
        <p>{{ title }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    path: String,
    title: String,
    subtitle: String,
  },
};
</script>

<style lang="scss">
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
.bg_gold:hover img {
  visibility: hidden;
}
.bg_gold:hover .backdrop_image {
  visibility: visible;
}
</style>