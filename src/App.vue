<template>
  <div id="app">
    <AppHero />
    <AppMain />
  </div>
</template>

<script>


import AppHero from "./components/AppHero";
import AppMain from "./components/AppMain";
// import stickyjs from 'sticky-js';


export default {
  name: "App",
  components: {
    AppHero,
    AppMain,
  },
  mounted() {
    // console.log('mounted hook worked')
    // new stickyjs('.select');
    // new stickyjs('.header-select')
    // console.log(sticky);
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
html. body {
  height: 100%;
}
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-size:18px;
}

</style>
