<script>
    import FooterLogoBg from './FooterLogoBg.vue' ;
    export default{
        name: 'FooterTop',
        components: {
            FooterLogoBg,
        },
        data(){
            return{
                FooterTitle: {
                    DcComics:[
                        {
                            title: 'DC COMICS'
                        },
                        {
                            name:'Character',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Comics',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Movies',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'TV',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Games',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Videos',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'News',
                            active:'false',
                            link: '#',
                        },
                    ],
                    Shop:[
                        {
                            title: 'SHOP'
                        },
                        {
                            name:'Shop DC',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Shop DC Collectibles',
                            active:'false',
                            link: '#',
                        },

                    ],
                    Dc:[
                        {
                            title: 'DC'
                        },
                        {
                            name:'Terms Of Use',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Privacy policy',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Ad Choices',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Advertising',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Jobs',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Subscriptions',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Talent Workshops',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'CPSC Certificates',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Rating',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Shop Help',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'Contact Us',
                            active:'false',
                            link: '#',
                        },
                    ],
                    Sites:[
                        {
                            title: 'SITES'
                        },
                        {
                            name:'DC',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'MAD Magazine',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'DC Kids',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'DC Universe',
                            active:'false',
                            link: '#',
                        },
                        {
                            name:'DC Power Visa',
                            active:'false',
                            link: '#',
                        },
                    ],
                }

            }
        }
    }
</script>

<template>
    <div class="footer-top">
        <FooterLogoBg/>
        <div class="container">
            <ul v-for="footerItem in FooterTitle">
                <li v-for="item in footerItem" class="title">
                    <div class="title">
                        {{item.title}}
                    </div>
                    <div class="link">
                        {{item.name}}
                    </div>
                </li>
            </ul>

        </div>
        
    </div>
</template>

<style lang="scss" scoped>
    .footer-top {
        padding: 50px;
        display: flex;
        justify-content: flex-start;
        width:500px;
    }
    .container{
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        position: relative;   
        max-height: 260px;
    }
    ul {
        display: flex;
        flex-direction: column;
        margin-bottom: 20px ;
        width: 200px;

    }
    .title {
        font-size: 25px;
        color: white;
        font-weight: bold;
    }
    .link {
        color: #959595;
        font-size: 14px;
    }
</style>