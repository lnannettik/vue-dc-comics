<template>
  <div id="app">
    <!-- HEADER -->
    <Header />

    <!-- MAIN -->
    <main></main>

    <!-- FOOTER -->
    <footer></footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'; 
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">

  /* GENERAL RESET */
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: sans-serif;
  }

  img {
    max-width: 100%;

  }


  // UTILITIES
  .container {
    max-width: 1170px;
    margin: 0 auto;
    padding: 0 16px;

  }

  .text-center {
    text-align: center;
  }




</style>
