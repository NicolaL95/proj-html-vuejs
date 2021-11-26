<template>
  <div id="card_component">
    <div class="container">
      <div class="row">
        <div
          class="card_container text-center col-3 lg_text bc_bg"
          v-for="(card, index) in cardGenerator"
          :key="index"
        >
          <i :class="cardGenerator[index].icon"></i>
          <p>{{ cardGenerator[index].name }}</p>
          <p class="">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et ratione
            amet aspernatur dolore. Quibusdam, fugiat.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cardGenerator: [
        {
          icon: "fas fa-building",
          name: "Buildings",
        },
        { icon: "fas fa-sync-alt", name: "Renovate" },
        {
          icon: "fas fa-home",
          name: "Construct",
        },
        {
          icon: "fas fa-truck",
          name: "Exclusive",
        },
      ],
    };
  },
};
</script>

<style>
.bc_bg {
}
</style>