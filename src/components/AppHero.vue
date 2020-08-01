<template>
  <section class="section hero">
    <div class="hero__container">
        <AppHeader />
        <div class="main__image">
            <img src="../assets/loto-kegs.png" alt="" class="main__pic">
        </div>
    </div>
  </section>
</template>

<script>
import AppHeader from "./AppHeader";

export default {
  components: {
    AppHeader,
  },
};
</script>

<style>
    .section  {
        height: 65.5vh;
    }
.hero {
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url('../assets/loto-background.png');
}
.hero__container {
    display: flex;
    flex-direction: column;
    width: 100%;
    max-width: 1077px;
    margin: 0 auto;
    height: 100%;
    padding: 54px 0 92px 0;
}
    .main__image {
        display: flex;
        justify-content: center;
        margin-top: auto;
    }
.main__pic {
    display: block;
    width: 100%;
    max-width: 592px;
    height: auto;
}

</style>
