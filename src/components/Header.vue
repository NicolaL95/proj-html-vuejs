<template>
  <div id="header_container">
    <div
      class="
        header_flex
        d-flex d-flex
        justify-content-between
        align-items-center
        pb-3
        pt-3
      "
    >
      <img
        src="../assets/construction_logo.png"
        alt="Avada Construction logo"
      />
      <nav
        class="
          header_navigator
          d-flex
          justify-content-between
          align-items-center
        "
      >
        <a href="">HOME</a>
        <a href="">ABOUT</a>
        <a href="">SERVICES</a>
        <a href="">WORK</a>
        <a href="">ARTICLES</a>
        <button class="border-0 quote_button button_size">GET QUOTE</button>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
#header_container {
  .header_flex {
    padding: 0 100px;
    img {
      height: 65px;
    }
    .header_navigator {
      width: 33%;
      a {
        text-decoration: none;
        color: #6b6868;
        transition: color 0.2s;
      }
      /* HOVER */
      a:hover {
        color: #fed23f;
      }
    }
  }
}
</style>