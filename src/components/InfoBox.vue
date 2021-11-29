<template>
  <div class="info_desc">
    <div class="container inf_size">
      <h3 class="lg_text">{{ title }}</h3>
      <div class="by mt-3 mb-3"></div>
      <p class="lg_text">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse sunt at
        unde, atque consequuntur adipisci corporis eum dolorem blanditiis
        maxime!
      </p>
    </div>
  </div>
</template>

<script>
export default {
  props: { title: String },
};
</script>

<style>
.inf_size {
  width: 33%;
  text-align: center;
}
</style>