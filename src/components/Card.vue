<template>
  <div id="card_component">
    <div class="container mw_17">
      <div class="row">
        <div class="col-3" v-for="(card, index) in cardGenerator" :key="index">
          <div class="card_flipper">
            <div class="card_container text-center position-relative b_rounded">
              <div
                class="
                  card_container_frontdrop
                  s_text
                  w-100
                  h-100
                  position-absolute
                  abs_center
                  p_40_20
                "
              >
                <div class="icon_b">
                  <i :class="cardGenerator[index].icon"></i>
                </div>
                <h4 class="mt-2">{{ cardGenerator[index].name }}</h4>
                <p class="m-0">
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et
                  ratione amet aspernatur dolore. Quibusdam, fugiat.
                </p>
              </div>
              <div
                class="
                  card_container_backdrop
                  position-absolute
                  w-100
                  h-100
                  p_40_20
                  no_abs_center
                "
              >
                <h5>{{ cardGenerator[index].backTitle }}</h5>
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et
                  ratione amet aspernatur dolore. Quibusdam, fugiat.
                </p>
                <button class="border-0 quote_button_l button_size">
                  GET QUOTE
                </button>
              </div>
            </div>
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
          backTitle: "ARTFULLY CRAFTED",
        },
        { icon: "fas fa-sync-alt", name: "Renovate", backTitle: "FRESHLY NEW" },
        {
          icon: "fas fa-home",
          name: "Construct",
          backTitle: "PERFECT LINES",
        },
        {
          icon: "fas fa-truck",
          name: "Exclusive",
          backTitle: "PLANNING",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.b_rounded {
  border-radius: 10px;
}
.card_flipper {
  perspective: 1000px;
  width: 100%;
}
.card_container {
  width: 350px;
  height: 300px;
  padding: 20px;
  background-color: #eeeeee;
  transition: all 0.4s ease-in-out;
  transform-style: preserve-3d;
  cursor: pointer;
  .p_40_20 {
    padding: 50px 20px 40px;
  }
  .s_text {
    color: #666665;
  }

  h4 {
    color: black;
    font-size: 1.8rem;
  }
  .icon_b {
    display: inline-block;
    font-size: 1.5rem;
    border-radius: 50%;
    border: 1px solid #6b6868;
    padding: 10px 15px;
  }
  .i_c {
    padding: 0 3px;
  }
}
/* BACKDROP CARD */
.card_container:hover {
  transform: rotate3d(0, 1, 0, -180deg);
}
.card_container_backdrop {
  transform: rotate3d(0, 1, 0, -180deg);
  backface-visibility: hidden;
  width: 100%;
  height: 100%;
}

.card_container_frontdrop {
  width: 100%;
  height: 100%;
}

/* HOVER */

.card_container:hover {
  background-color: #fed23f;
}

.card_container:hover > .card_container_frontdrop {
  visibility: hidden;
}

/* .card_container:hover > .card_container_backdrop {
  visibility: visible;
} */
</style>