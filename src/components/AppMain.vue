<template>
  <main class="main">
    <AppNav />
    <div class="main__container">
      <AppAbout />
      <AppPrizes />
      <AppTicket />
      <AppRules />
      <AppTours />
      <AppResults />
      <AppWin />

    </div>
    <AppFooter />
  </main>
</template>

<script>
import AppNav from "./AppNav";
import AppAbout from "./AppAbout";
import AppPrizes from "./AppPrizes";
import AppTicket from "./AppTicket";
import AppRules from "./AppRules";
import AppTours from "./AppTours";
import AppResults from "./AppResults";
import AppWin from "./AppWin";
import AppFooter from "./AppFooter";

export default {
  components: {
    AppFooter,
    AppWin,
    AppResults,
    AppTours,
    AppRules,
    AppNav,
    AppAbout,
    AppPrizes,
    AppTicket,

  },
};
</script>

<style>
  /*@import "/src/assets/css/fonts/fonts.css";*/
  h1 {
    font-size: 36px;
  }

  .main__container {
    max-width: 740px;
    margin: 0 auto;
    text-align: left;
    font-family: 'Roboto Condensed', sans-serif;
  }
</style>
