<script>
import ContentSection from './ContentSection.vue' ;
import ServiceSection from './ServiceSection.vue' ;
    export default{
        name: 'AppMain',
        components: {
            ContentSection,
            ServiceSection,
        },
    }
</script>

<template>
    <ContentSection/>
    <ServiceSection/>
</template>

<style lang="scss">

</style>
