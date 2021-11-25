<template>
  <header>
        <div class="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div>
                <ul>
                    <li>
                        <a href="">Characters</a>
                    </li>
                    <li>
                        <a href="">Comics</a>
                    </li>
                    <li>
                        <a href="">MOvies</a>
                    </li>
                    <li>
                        <a href="">Tv</a>
                    </li>
                    <li>
                        <a href="">Games</a>
                    </li>
                    <li>
                        <a href="">Collectibles</a>
                    </li>
                    <li>
                        <a href="">Video</a>
                    </li>
                    <li>
                        <a href="">Fans</a>
                    </li>
                    <li>
                        <a href="">News</a>
                    </li>
                    <li>
                        <a href="">Shop</a>
                    </li>
                </ul>
            </div>
        </div>
  </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>

    header{
        width: 100%;
        height: 103px;
        background-color: white;
        
    }

    .container{
        display: flex;
        justify-content: space-between;
        align-content: center; 
    }

    .container div{
        display: flex;
        align-items: center;
        justify-content: center;
    }

    img{
        height: 80%;
    }

    ul{
        list-style: none;
        /*height 100% elimina il centramento verticale della lista*/
    }

    li{
        float: left;
        height: 100%;
    }

    li a {
        display: block;
        color: black;
        text-align: center;
        padding: 16px;
        text-decoration: none;
        height: 100%;
        /*teto maiuscolo*/
    }

    li a:hover {
        color: #007ef9;
        border-bottom: 1px solid #007ef9;
        /*il bordo spinge il blocco più in alto*/    
    }

</style>