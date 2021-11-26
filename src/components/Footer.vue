<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="list-box">
                    <div>
                        <ul>
                            <ol>Dc comics</ol>
                            <li v-for="li in listDcComics" :key="li">
                                <a href="#">{{li}}</a>
                            </li>
                        </ul>
                        <ul>
                            <ol>Shop</ol>
                            <li v-for="li in listShop" :key="li">
                                <a href="#">{{li}}</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <ol>Dc</ol>
                            <li v-for="li in listDc" :key="li">
                                <a href="#">{{li}}</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <ol>Sites</ol>
                            <li v-for="li in listSites" :key="li">
                                <a href="#">{{li}}</a>
                            </li> 
                        </ul>
                    </div>
                </div>
                <div class="dc-logo"></div>
            </div>
        </div>
        <div class="footer-bot">
            <div class="container">
                <div class="btn">
                    <a href="">Sign-up now!</a>
                </div>
                <div class="right">
                    <h2>Follow us</h2>
                    <img src="..\assets\img\footer-facebook.png" alt="">
                    <img src="..\assets\img\footer-twitter.png" alt="">
                    <img src="..\assets\img\footer-youtube.png" alt="">
                    <img src="..\assets\img\footer-pinterest.png" alt="">
                    <img src="..\assets\img\footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data() {
      return {
        listDcComics:['characters', 'comics', 'movies', 'tv', 'games', 'videos', 'news'],
        listShop:['shop DC', 'shop DC collectibles'],
        listDc:['terms of use', 'privacy policy (new)', 'ad choices', 'advertising', 'jobs', 'subscription', 'talent workshop', 'CPSC certificates', 'ratings', 'shop help', 'contact us'],
        listSites:['DC', 'MAD magazine', 'DC kids', 'DC universe', 'DC Power Visa'],
      }
   }
}

</script>

<style lang="scss">

/*footer top*/
    .footer-top{
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: cover;
        
        .container{
            display: flex;
            
            .list-box{
                display: flex;
                padding: 50px 0;
            }
        }

        .dc-logo{
            margin-left: 50px;
            width: 53%;
            background-image: url("../assets/img/dc-logo-bg.png");
            background-position: center;
        }
    }

    .footer-top ul{
        color: white;
        list-style: none;
        padding: 15px 50px 0 0;
        
        ol{
            font-weight: bold;
            font-size: 22px;
            text-transform: uppercase;
            padding-bottom: 10px;
            color: white;
        }

        li a{
            display: block;
            color: grey;
            text-decoration: none;
            text-transform: capitalize;

            &:hover{
                color: white;
            }
        }
    }

/*footer bottom*/
    .footer-bot{
        background-color: #303030;
        color: white;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;

            .right{
                display: flex;
                align-items: center;
            }
        }
    
    } 

    .footer-bot .btn{
        border: solid 2px #0282f9;
        padding: 10px;


        a{
            display: block;
            text-decoration: none;
            color: white;
            text-transform: uppercase;
        }
    }
    
    .footer-bot h2{
        color: #0282f9;
        text-transform: uppercase;
    }

    .footer-bot img{
        padding: 0 0 0 20px;
    }

</style>