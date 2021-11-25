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
        background-color: white;
        position: fixed;
    }

    .container{
        width: 70%;
        margin: 0 15%;
        display: flex;
        justify-content: space-between;
        align-content: center; 
    }

    .container div{
        display: flex;
        align-items: center;
    }

    ul{
        list-style: none;
    }

    li{
        float: left;
    }

    li a {
        display: block;
        color: black;
        text-align: center;
        padding: 16px;
        text-decoration: none;
    }

    li a:hover {
        color: blue;
        border-bottom: 1px solid blue;
        /*il bordo spinge il blocco più in alto*/    
    }

</style>