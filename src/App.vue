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

/* BUTTONS */
#app {
  font-family: "Montserrat", sans-serif;
}
.quote_button {
  background-color: #fed23f;
  color: #6b6868;
}

.bw_button {
  color: white;
  background-color: #31312f;
}

.button_size {
  padding: 10px 40px;
}

/* text */
.lg_text {
  color: #6b6868;
}
.minus_text {
  font-size: 0.8rem;
}
</style>
