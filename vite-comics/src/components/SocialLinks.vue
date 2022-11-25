<script>
    export default{
        name: 'SocialLinks',
        components: {
            //AppName
        },
        data(){
            return {
                socials: [
                    {
                        name: 'facebook',
                        icon: '<i class="fa-brands fa-facebook"></i>',
                        link: '#',
                    },
                    {
                        name: 'twitter',
                        icon: '<i class="fa-brands fa-twitter"></i>',
                        link: '#',
                    },
                    {
                        name: 'youtube',
                        icon: '<i class="fa-brands fa-youtube"></i>',
                        link: '#',
                    },
                    {
                        name: 'pinterest',
                        icon: '<i class="fa-brands fa-pinterest"></i>',
                        link: '#',
                    },
                    {
                        name: 'location',
                        icon: '<i class="fa-duotone fa-location-dot"></i>',
                        link: '#',
                    },

                ]
            }
        }
    }
</script>

<template>
    <div class="social-links">
        <ul>
            <li> <span>FOLLOW US</span></li>
            <li v-for="item in socials">{{item.icon}}</li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
    ul {
        display: flex;
    }
    li i{
        color: #797979;
    }
    .social-links {
        max-width: 20%;
    }
</style>