<script>
    import HeroJumbotron from './HeroJumbotron.vue';
    import AppCard from './AppCard.vue';
    export default{
        name: 'ContentSection',
        components: {
            HeroJumbotron,
            AppCard,
        },
        data() {
            return{
           
            }
        }
    }
</script>

<template> 
    <HeroJumbotron/>
    <section>     
        <div class="container">
            <AppCard/>
        </div>   
    </section>
</template>

<style lang="scss" scoped>
    section {
        color: white;
        padding: 50px 20px;
        background-color: #1c1c1c;
    }
    .container {
        padding: 20px 0;
    }
</style>