<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="list-box">
                    <div>
                        <ul>
                            <ol>Dc comics</ol>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                        </ul>
                        <ul>
                            <ol>Shop</ol>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <ol>Dc</ol>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <ol>Sites</ol>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Characters</a>
                            </li>  
                        </ul>
                    </div>
                </div>
                <div class="dc-logo"></div>
            </div>
        </div>
        <div class="footer-bot">
            <div class="container">
                <div class="btn">Sign-up now!</div>
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
    name: 'Footer'
}
</script>

<style>
/* non funziona lo scoped*/
/*footer top*/
    .footer-top{
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: cover;
    }

    .footer-top .container{
        display: flex;
    }

    .footer-top .list-box{
        display: flex;
        padding: 50px 0;
    }

    .footer-top ul{
        color: white;
        list-style: none;
        padding: 15px 50px 0 0;
    }

    .footer-top ol{
        font-weight: bold;
        font-size: 22px;
        text-transform: uppercase;
        padding-bottom: 10px;
        color: white;
    }

    .footer-top li a{
        display: block;
        color: grey;
        text-decoration: none;
    }

    .footer-top li a:hover{
        color: white;
    }

    .footer-top .dc-logo{
        margin-left: 50px;
        width: 53%;
        background-image: url("../assets/img/dc-logo-bg.png");
        background-position: center;
    }

/*footer bottom*/
    .footer-bot{
        background-color: #303030;
        color: white;
    }

    .footer-bot .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 0;
    }

    .footer-bot .right{
        display: flex;
        align-items: center;
    }

    .footer-bot h2{
        color: #0282f9;
        text-transform: uppercase;
    }

    .footer-bot img{
        padding: 0 0 0 20px;
    }

</style>