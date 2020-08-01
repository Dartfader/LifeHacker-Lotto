<template>
    <div class="app-tours">
        <h1 class="section__title">Туры лотереи</h1>
        <div class="app-game__image">
            <img src="../assets/tour.png" alt="" class="app-game__pic pic" />
        </div>
        <ul class="app-game__list list">
            <li class="app-game__item item">
                <div class="app-game__image">
                    <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                </div>
                <div class="app-game__content item__content">
                    <h3 class="app-game__title">Первый тур</h3>
                    <div class="app-game__text item__text">
                        Выигрывают билеты, в которых пять чисел в любой из строк раньше других совпадут с номерами бочонков,
                        вынутых ведущим из мешка. Раньше других — значит раньше, чем в других билетах, участвующих
                        в тираже.
                    </div>
                </div>
            </li>
            <li class="app-game__item item">
                <div class="app-game__image">
                    <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                </div>
                <div class="app-game__content item__content">
                    <h3 class="app-game__title">Второй тур</h3>
                    <div class="app-game__text item__text">
                        Здесь выигрывают те билеты, в которых оказались зачёркнуты все 15 чисел в верхнем или нижнем поле.
                        Если это случилось на пятнадцатом ходу, поздравляем — вы выиграли джекпот.
                    </div>
                </div>
            </li>
            <li class="app-game__item item">
                <div class="app-game__image">
                    <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                </div>
                <div class="app-game__content item__content">
                    <h3 class="app-game__title">Третий и последующие туры</h3>
                    <div class="app-game__text item__text">
                        На этих этапах выигрывают билеты, в которых раньше других совпадут все 30 чисел.
                    </div>
                </div>
            </li>
            <li class="app-game__item item">
                <div class="app-game__image">
                    <img src="../assets/Group2.svg" alt="2" class="app-prizes__pic" />
                </div>
                <div class="app-game__content item__content">
                    <h3 class="app-game__title">«Кубышка»</h3>
                    <div class="app-game__text item__text">
                        Дополнительный тур, который проводят не всегда. В нём выигрывают билеты,
                        где все невыпавшие в тираже числа оказываются в одном поле — верхнем или нижнем.
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "AppTours"
    }
</script>

<style>

</style>