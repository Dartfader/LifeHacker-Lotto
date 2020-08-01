<template>
    <div class="app-prizes">
        <div class="app-prizes__container">
            <h1 class="section__title list__title">Как получить выигрыш</h1>
            <div class="app-prizes__image">
                <img src="../assets/women.png" alt="" class="app-prizes__pic pic" />
            </div>

            <div class="app-prizes__content">
                <p class="app-prizes__text">
                    Чтобы получить выигрыш, нужно предъявить паспорт и лотерейный билет.
                    Забрать приз можно в течение шести месяцев после обращения за выигрышем и подачей заявления.
                </p>
                <p class="app-prizes__text">
                    Если в этот срок получить выигрыш по какой-то причине не удалось,
                    нужно заполнить специальную форму, которая есть на сайте «Столото», и обратиться в лотерейный центр в Москве.
                </p>
                <p class="app-prizes__text">
                В этом случае выигрыш будет ждать победителя ещё три года. Все выигрыши, за которыми никто не пришёл, перечисляются в государственный бюджет.
                </p>
            </div>

            <h2 class="list__title">Где забрать деньги</h2>
            <p class="app-prizes__text">
                В зависимости от суммы есть несколько способов забрать приз:
            </p>
                <ul class="app-reviews__list list">
                    <li class="app-reviews__item item">
                        <div class="app-reviews__image">
                            <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                        </div>
                        <div class="app-reviews__content item__content">
                            <h3 class="app-reviews__title">
                                Перевести на баланс кошелька «Столото» — до 100 000 рублей
                            </h3>
                            <p class="app-reviews__text item__text">
                                Этот вариант подойдёт, если вы указали номер телефона при покупке.
                                Зарегистрируйтесь на сайте с этим номером и выберите «Перевести выигрыш в кошелёк» на странице информации о билете.
                                Эти деньги можно использовать для покупки новых билетов.
                            </p>
                        </div>
                    </li>
                    <li class="app-reviews__item item">
                        <div class="app-reviews__image">
                            <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                        </div>
                        <div class="app-reviews__content item__content">
                            <h3 class="app-reviews__title">
                                Забрать в точке продаж — до 2 000 рублей
                            </h3>
                            <p class="app-reviews__text item__text">
                                Чтобы найти подходящую точку, нужно выбрать на странице с <a href="">картой</a>  «Столото» пункт «Получить выигрыш» и ввести сумму выигрыша.
                            </p>
                        </div>
                    </li>
                    <li class="app-reviews__item item">
                        <div class="app-reviews__image">
                            <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                        </div>
                        <div class="app-reviews__content item__content">
                            <h3 class="app-reviews__title">
                                Перевести на лицевой счёт — от 100 000 рублей
                            </h3>
                            <p class="app-reviews__text item__text">
                                Для получения выигрыша нужно предоставить комплект документов и реквизиты счёта. Подробности — на
                                <a href="">сайте «Столото»</a>.
                            </p>
                        </div>
                    </li>
                    <li class="app-reviews__item item">
                        <div class="app-reviews__image">
                            <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                        </div>
                        <div class="app-reviews__content item__content">
                            <h3 class="app-reviews__title">
                                В лотерейном центре «Столото» в Москве можно получить любую сумму.
                            </h3>

                        </div>
                    </li>
                </ul>
            <h2 class="list__title">Какие налоги придётся заплатить</h2>
            <div class="app-prizes__content">
                <p class="app-prizes__text">
                    Налог с выигрыша для россиян составляет 13%. Для нерезидентов РФ — 30%. Если за год вы выиграли не больше 4 000 рублей, ничего платить не нужно.
                </p>
                <p class="app-prizes__text">

                    Выплату от 15 000 рублей вы получите уже с удержанным налогом 13%. Если выигрыш меньше 15 000 рублей,
                    нужно подать в налоговый орган по месту жительства декларацию, оформленную по форме 3-НДФЛ, а потом заплатить налог в банке или онлайн.
                    То же самое придётся сделать для получения вещевого приза: например, автомобиля или квартиры.
                </p>
                <p class="app-prizes__text">
                    Каждый выигрыш фиксируется в системе Федеральной налоговой службы.
                    Все невостребованные выигрыши перечисляются в госбюджет, так как организатор лотерей — государство.
                </p>
            </div>

            <button class="button">
                Играть в «Русское лото»
            </button>
            </div>

        </div>
</template>

<script>
    export default {
        name: "AppWin"
    }
</script>

<style scoped>
    .button {
        display: flex;
        margin-top: 90px;
        width: 100%;
        height: 50px;
        align-items: center;
        justify-content: center;
        background: #ed5e42;
        border: none;
        color: white;
        font-size: 24px;
        font-weight: bold;
        font-family: 'Roboto Condensed';
    }
</style>