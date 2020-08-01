<template>

    <header data-margin-top="0" class="header header-select">
        <div class="header__container">
            <div class="logo">
                <div class="left__logo">
                    <a href="#" class="item__link">
                        <img src="../assets/logos-white.svg" alt="" class="item__pic">
                    </a>
                </div>
                <div class="right__logo">
                    <img src="../assets/logos-lotto-white.svg" alt="" class="item__pic">
                </div>
            </div>
            <nav class="nav__links">
                <ul class="nav__list">
                    <li class="nav__item">
                        <a href="#" class="item__link">
                            <img src="../assets/fasebook.svg" alt="" class="item__pic">
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#" class="item__link">
                            <img src="../assets/fasebook.svg" alt="" class="item__pic">
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#" class="item__link">
                            <img src="../assets/fasebook.svg" alt="" class="item__pic">
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>
<script>
    // import stickyjs from 'sticky-js'
    // export default  {
    //     mounted() {
    //         // console.log('mounted hook worked')
    //         const sticky = new stickyjs('.target');
    //         // new Sticky([selector:string], [global options:object])
    //         console.log(sticky);
    //     }
    // };

</script>
<style scoped>
    .header {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
    }

    .header__container {
        max-width: 1092px;
        display: flex;
        /*margin-top: 16px;*/
        flex: 1;
        justify-content: space-between;
    }

    .logo {
        display: flex;
    }

    .left__logo {
        margin-right: 35px;
    }
</style>
