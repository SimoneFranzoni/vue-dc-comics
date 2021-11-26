<template>
    <main>
        <section class="jumbotrone"></section>

        <div class="container">
            <h2>Current Series</h2>
        </div>

        <div class="container-sup">
            <div class="container comicsBox">
                <TemplateComic
                v-for="(comic, index) in Comics"
                :key="index"
                :comic="comic"
                />
            </div>    
        </div>

        <button>
            <a href="">Load More</a>
        </button>

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

import Comics from '../assets/data/Books';
import TemplateComic from './TemplateComic.vue'

export default {

    name: 'Main',
    components: {
        TemplateComic
    },
    data() {
        return {
            Comics
        }
    }
}
</script>

<style lang="scss">

    .jumbotrone{
        background-image: url("../assets/img/jumbotron.jpg");
        background-size: cover;
        width: 100%;
        height: 350px;     
    }

    main{
        h2{
            padding: 15px 50px;
            display: inline-block;
            color: #fff;
            text-transform: uppercase;
            transform: translateY(-50%);
            background-color: #007ef9;
        }

        button{
            padding: 8px 40px;
            font-weight: bold;
            text-transform: uppercase;
            border: none;
            background-color: #007ef9;
        }

        a{
            color: #fff;
            text-decoration: none;
        }

    }

    .comicsBox{
        display: flex;
        flex-wrap: wrap;
    }

    @import "../assets/style/main-inf.scss";
    
    @import "../assets/style/main-sup.scss";
    
</style>