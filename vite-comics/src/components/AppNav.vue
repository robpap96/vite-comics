<script>
    export default{
        name: 'AppNav',
        data() {
            return{
                items: [ 
                    {
                        href: '#',
                        label: 'Characters',
                        active: false,   
                    },  
                    {
                        href: '#',
                        label: 'Comics',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Movies',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'TV',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Games',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Collectibles',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Videos',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Fans',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'News',
                        active: false,   
                    },
                    {
                        href: '#',
                        label: 'Shop',
                        active: false,   
                    },
                ]
            }    
        }
    }

</script>

<template>
    <ul class="d-flex">
        <li v-for="item in items">{{item.label}}</li>

    </ul>
</template>

<style lang="scss">
</style>
