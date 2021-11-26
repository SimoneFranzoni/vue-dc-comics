<template>
  <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div>
               <ul>
                    <li v-for="item in navList" :key="item">
                        <a>{{item}}</a>
                    </li>
                </ul>
            </div>
        </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return{
            navList: ['characters', 'comics', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop'],
        }
    }

}
</script>

<style lang="scss">

    header{
        width: 100%;
        height: fit-content;
        background-color: white;

        .container{
            display: flex;
            justify-content: space-between;
            align-content: center; 

            div{
                display: flex;
                align-items: center;
                justify-content: center;
            }

        }

    }


    header img{
        height: 80%;
    }

    header ul{
        list-style: none;
        /*height: 100%; /*elimina il centramento verticale della lista*/

        li{
            float: left;
            height: 100%;

            a {
                display: block;
                color: black;
                text-align: center;
                padding: 12px;
                text-decoration: none;
                height: 100%;
                text-transform: uppercase;
                font-size: 13px;
                font-weight: bold;
                /*teto maiuscolo*/

                &:hover {
                    color: #007ef9;
                    border-bottom: 3px solid #007ef9;
                     /*il bordo spinge il blocco più in alto*/   
                }
            }

        }

    }  


</style>