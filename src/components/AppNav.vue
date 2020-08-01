<template>

  <div data-sticky-wrap="false" data-margin-top="40" data-sticky-class="select--sticky" class="select">

      <AppHeader class="select__header"/>
      <div class="nav__bottom">
        <div class="nav__container">
        <ul class="nav__list">
          <li v-for="item in navList" :key="item.text" class="nav__item">
            <a :href="item.link" class="nav__link">{{ item.text }}</a>
          </li>
          <!-- <li class="app-nav__item">
            <a href="#" class="app-nav__link">Что можно выиграть</a>
          </li> -->
          <!-- <li class="app-nav__item">
            <a href="#" class="app-nav__link">Где купить билет</a>
          </li>
          <li class="app-nav__item">
            <a href="#" class="app-nav__link">Как играть</a>
          </li>
          <li class="app-nav__item">
            <a href="#" class="app-nav__link">Туры лотереи</a>
          </li>
          <li class="app-nav__item">
            <a href="#" class="app-nav__link">Где узнать результаты</a>
          </li>
          <li class="app-nav__item">
            <a href="#" class="app-nav__link">Как получить выигрыш</a>
          </li> -->
        </ul>
      </div>
    </div>

  </div>

</template>

<script>
  import AppHeader from './AppHeader';
export default {
  components: {
    AppHeader
  },
  data() {
    return {
      navList: [
        {
          link: "#",
          text: "Что можно выиграть",
        },
        {
          link: "#",
          text: "Где купить билет",
        },
        {
          link: "#",
          text: "Как играть",
        },
        { link: "#", text: "Туры лотереи" },
        { link: "#", text: "Где узнать результаты" },
        {
          link: "#",
          text: "Как получить выигрыш",
        },
      ],
    }
  },
};
</script>

<style>
  .nav__container {
      max-width: 1248px;
      display: flex;
      /* height: 100%; */
      width: 100%;
      /* flex: 1; */
      justify-content: space-between;
      /* width: 100%; */
  }
  @keyframes popup {
    0% {
      transform: translateY(100px);
      opacity: 0;
    }
    100% {
      transform: translateY(0);
      opacity: 1;
      /*position: relative;*/
    }

  }
  .select--sticky .header {
    animation: popup .4s;
    position: relative;
    background-color: orange;
    transition: all .7s;
  }

  .select__header {
      position: absolute;
      width: 100%;
      margin: 0 auto;
      z-index: -20;
  }

  .nav__bottom {
      display: flex;
      /* height: 119px; */
      background: transparent;
      justify-content: center;
      align-items: center;
      width: 100%;
  }
  .nav__bottom--select {
    background-color: orange;
    transition: all 1s;
  }

  .select--sticky .nav__container {
    max-width: 1125px;
  }

  .nav__list {
      display: flex;
      flex: 1;
  }

  .nav__item {
      display: flex;
      height: 100%;
      flex: 1;
      margin-right: 18px;
      list-style-type: none;
  }

  .nav__item:last-child {
      margin-right: 0;
  }

  .nav__link {
      display: flex;
      align-items: center;
      font-size: 16px;
      text-decoration: none;
      color: #919DA3;
      flex: 1;
      padding: 61px 0 38px 0;
  }
</style>
