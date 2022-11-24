<script>
import AppLogo from './AppLogo.vue' ;
import AppNav from './AppNav.vue' ;
    export default{
        name: 'AppHeader',
        components: {
            AppLogo,
            AppNav,
        }
    }
</script>

<template>
    <div class="container">
        <div class="box">
            <AppLogo/>
            <AppNav/>
        </div>
   
    </div>
</template>

<style lang="scss">
    .box {
        padding: 20px 10px;
    }
</style>
