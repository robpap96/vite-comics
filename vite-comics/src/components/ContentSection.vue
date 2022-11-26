<script>
    import HeroJumbotron from './HeroJumbotron.vue';
    export default{
        name: 'ContentSection',
        components: {
            HeroJumbotron,
        },
        data() {
            return{
                msg: '-->Content goes here<--'
            }
        }
    }
</script>

<template> 
    <HeroJumbotron/>
    <section> 
       
        <div class="container">
 
        </div>
        
    </section>
</template>

<style lang="scss" scoped>
    section {
        color: white;
        padding: 50px 20px;
    }
</style>