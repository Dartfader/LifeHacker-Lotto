<template>
  <div class="app-prizes">
    <div class="app-prizes__container">
      <h1 class="section__title">Что можно выиграть</h1>
      <div class="app-prizes__image">
        <img src="../assets/prizes.png" alt="" class="app-prizes__pic pic" />
      </div>
      <div class="app-prizes__content">
        <p class="app-prizes__text">
          В первых турах можно выиграть от нескольких тысяч до нескольких
          миллионов рублей, а также автомобили, загородные дома и путешествия.
          Все выигрыши можно получить в денежном эквиваленте.
        </p>
        <p class="app-prizes__text">
          Самый крупный приз
          — джекпот. Это десятки и даже сотни миллионов рублей, он накапливается
          от тиража к тиражу. Джекпот можно выиграть, если 15 чисел верхнего или
          нижнего поля билета совпадут с номерами на первых 15 бочонках,
          вытянутых ведущим из мешка. Сумма рекордного джекпота в «Русском лото»
          уже больше 900 000 000 рублей.
        </p>
      </div>
      <div class="app-prizes__image">
        <img src="../assets/jackpot.png" alt="" class="app-prizes__pic pic" />
      </div>
      <div class="app-prizes__content">
        <p class="app-prizes__text">
          Призовой фонд формируется из половины стоимости всех проданных
          билетов. С начала 2019 года общая сумма выигрышей составила свыше 3
          миллиардов рублей. Победителями стали около 2 миллионов участников
          лотереи.
        </p>
      </div>
      <div class="app-prizes__reviews app-reviews">
        <h2 class="list__title">Самые крупные выигрыши в «Русском лото»</h2>
        <ul class="app-reviews__list list">
          <li class="app-reviews__item item">
            <div class="app-reviews__image item__image">
                <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
            </div>
            <div class="app-reviews__content item__content">
              <h3 class="app-reviews__title">
                Наталья Власова — 506 000 000 рублей.
              </h3>
              <p class="app-reviews__text item__text">
                1 204-й тираж, трансляция от 5 ноября 2017 года. Деньги
                пенсионерка решила потратить на покупку жилья, отдых,
                образование дочери и благотворительность.
              </p>
            </div>
          </li>
          <li class="app-reviews__item item">
            <div class="app-reviews__image">
              <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
            </div>
            <div class="app-reviews__content item__content">
              <h3 class="app-reviews__title">
                Любовь и Сергей Догоровы — 500 000 000 рублей.
              </h3>
              <p class="app-reviews__text item__text">
                1 264-й тираж, трансляция от 1 января 2019 года. Победители
                вложились в путешествия, покупку квартиры, помощь родственникам
                и благотворительность. Часть суммы собираются инвестировать.
              </p>
            </div>
          </li>
          <li class="app-reviews__item item">
            <div class="app-reviews__image">
              <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
            </div>
            <div class="app-reviews__content item__content">
              <h3 class="app-reviews__title">
                Николай и Оксана Мирошниченко — 500 000 000 рублей.
              </h3>
              <p class="app-reviews__text item__text">
                1 264-й тираж, трансляция от 1 января 2019 года. Полмиллиарда
                планируют потратить на путешествия, выплату ипотеки, помощь
                родственникам и благотворительность.
              </p>
            </div>
          </li>
        </ul>
      </div>
      <p class="app-prizes__text">
        В России все лотереи государственные и регулируются Федеральным законом
        № 138-ФЗ. Организаторами розыгрышей выступают Министерство спорта РФ и
        Министерство финансов РФ. Они утверждают условия лотерей и заключают
        контракты с операторами. Часть денег, вырученных от продажи билетов,
        идёт на финансирование государственных программ по развитию физической
        культуры и спорта.
      </p>
    </div>
  </div>
</template>

<style>

  .app-prizes__text {
    padding-top: 37px;
    line-height: 26px;
    letter-spacing: 1.2px;
  }
  .list__title {
    font-size: 30px;
    line-height: normal;
  }
  .list {
    list-style: none;
  }
  .item {
    display: flex;
    margin: 0px 0px 55px 0px;
  }
  .item__content {
    margin-left: 28px;
  }

  .item__text {
    padding-top: 7px;
  }
</style>
