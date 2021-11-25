<template>
    <main>

        <div class="container-sup">
            <div class="container">
                <h1>Content goes here</h1>
            </div>
        </div>

        <div class="container-inf">
            <div class="container">
                <div class="box">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="">
                    <P>Digital Comics</P>
                </div>   
                <div class="box">
                    <img src="..\assets\img\buy-comics-merchandise.png" alt="">
                    <P>Digital Comics</P>
                </div>  
                <div class="box">
                    <img src="..\assets\img\buy-comics-subscriptions.png" alt="">
                    <P>Digital Comics</P>
                </div>  
                <div class="box">
                    <img src="..\assets\img\buy-comics-shop-locator.png" alt="">
                    <P>Digital Comics</P>
                </div>   
                <div class="box">
                    <img src="..\assets\img\\buy-dc-power-visa.svg" alt="">
                    <P>Digital Comics</P>
                </div>  
            </div>
        </div>

    </main>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style scoped>

    @import "../assets/style/main-inf.scss";
    
    @import "../assets/style/main-sup.scss";
    
    .container-inf{
    background-color: #0282f9;
    padding: 50px 5%;
    color: white;
    }

    .container-inf .container{
        display: flex;
        justify-content: space-evenly;
    }

    .container-inf .box{
        display: flex;
        align-items: center;    
    }

    .container-inf .box img{
        height: 50px;
        width: 40px;
    }

    .container-inf .box p{
        padding-left: 10px;
        text-transform: uppercase;
        font-size: 14px;
    }

</style>