<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
  },
};
</script>

<style lang="scss">
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
  padding: 5px 30px;
}

/* text */
.lg_text {
  color: #6b6868;
}
</style>
