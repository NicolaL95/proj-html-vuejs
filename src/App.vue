<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
/* CENTER POSITION */
.abs_center {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
.no_abs_center {
  top: 0;
  left: 0;
}
/* Z-index */
.z_index_over {
  position: relative;
  z-index: 2;
}

/* BUTTONS */
#app {
  font-family: "Montserrat", sans-serif;
}
.quote_button {
  background-color: #fed23f;
  color: #6b6868;
  transition: background-color 0.3s;
}

.quote_button_l {
  background-color: #ffe07b;
  color: #6b6868;
  transition: background-color 0.3s;
}

.bw_button {
  color: white;
  background-color: #31312f;
  transition: background-color 0.3s;
}

.button_size {
  padding: 10px 40px;
}

.button_size_b {
  font-size: 1.3rem;
}

/* TEXT */
.lg_text {
  color: #6b6868;
}
.minus_text {
  font-size: 0.8rem;
}

.text_b {
  font-size: 2.5rem;
}
/* SIZE */
.mw_17 {
  max-width: 1700px !important;
}

/* HOVER */
.quote_button:hover,
.quote_button_l:hover {
  background-color: #31312f;
  color: white;
}

.bw_button:hover {
  background-color: #fed23f;
  color: #6b6868;
}

.free_quote:hover {
  background-color: white;
}
</style>
