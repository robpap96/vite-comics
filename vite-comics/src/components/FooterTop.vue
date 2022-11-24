<script>
    import FooterLogoBg from './FooterLogoBg.vue' ;
    export default{
        name: 'FooterTop',
        components: {
            FooterLogoBg,
        },
    }
</script>

<template>
    <div class="footer-top">
        <FooterLogoBg/>
        <div class="container">
            <ul>
                <li>s</li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </div>
        
    </div>
</template>

<style lang="scss">
    .footer-top {
        background-image: url('../assets/footer-bg.jpg');
        display: flex;
        flex-direction: column;
        position: relative;
    }
</style>