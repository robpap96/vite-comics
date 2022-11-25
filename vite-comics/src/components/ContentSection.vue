<script>
    export default{
        name: 'ContentSection',
        components: {
            //AppName
        },
        data() {
            return{
                msg: '-->Content goes here<--'
            }
        }
    }
</script>

<template>
    <section>
        <div class="container">
            <h2> {{msg}}</h2>
        </div>
        
    </section>
</template>

<style lang="scss" scoped>
    section {
        color: white;
        background-color: black;
        padding: 50px 20px;
    }
</style>