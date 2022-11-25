<script>
import FooterTop from './FooterTop.vue' ;
import FooterBottom from './FooterBottom.vue' ;
    export default{
        name: 'AppFooter',
        components: {
            FooterTop,
            FooterBottom,
        },
    }
</script>

<template>
    <footer>
        <FooterTop/>
        <FooterBottom/>

    </footer>
</template>

<style lang="scss" scoped>
    footer{
        background-image: url('../assets/footer-bg.jpg');
    }
</style>
