<script>
    import SocialLinks from './SocialLinks.vue' ;
    export default{
        name: 'FooterBottom',
        components: {
            SocialLinks,
        },
        
    }
</script>

<template>
    <div class="footer-bottom">
        <div class="container">
            <div class="footer-bottom-btn">
                <button class="sign-up-btn">Sign Up Now!</button>
            </div>
            <SocialLinks/>
            
        </div>
        
    </div>
</template>

<style lang="scss" scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css') ;
    .container {
        padding: 50px;
        display: flex;
        justify-content: space-between;
    }
    .footer-bottom {
        position: relative;
        z-index: 10;
        background-color: #303030;
        padding: 0 50px;
    }
</style>