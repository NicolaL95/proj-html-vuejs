<template>
  <div id="card_component">
    <div class="container">
      <div class="row">
        <div class="col-3" v-for="(card, index) in cardGenerator" :key="index">
          <div class="card_container text-center lg_text bc_bg">
            <div class="icon_b">
              <i :class="cardGenerator[index].icon"></i>
            </div>
            <h4 class="mt-2">{{ cardGenerator[index].name }}</h4>
            <p class="m-0">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et
              ratione amet aspernatur dolore. Quibusdam, fugiat.
            </p>
          </div>
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
          icon: "far fa-building i_c",
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

<style lang="scss">
.card_container {
  padding: 20px;
  .icon_b {
    display: inline-block;
    font-size: 1.3rem;
    border-radius: 50%;
    border: 1px solid #6b6868;
    padding: 10px 15px;
  }
  .i_c {
    padding: 0 3px;
  }
}
.bc_bg {
  background-color: #bcbcbc;
}
</style>