<template>
    <div class="footer">
        <div class="footer__content">
            <div class="footer__text">© 2019 Лайфхакер</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "AppFooter"
    }
</script>

<style scoped>

    .footer {
        display: flex;
        position: relative;
        width: 100%;
        margin-top: 69px;
        /* bottom: 0; */
        /* right: 5%; */
        /* float: right; */
        align-items: center;
        justify-content: flex-end;
        height: 60px;
        background: black;
        color: white;
    }
    .footer__content {
        display: flex;
        position: absolute;
        right: 21%;
    }
</style>