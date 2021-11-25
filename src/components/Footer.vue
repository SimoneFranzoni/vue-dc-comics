<template>
    <footer>
        <div class="footer-top">
            <div class="container">
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
        </div>
        <div class="footer-bot">
            <div class="container">
                
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
    .footer-top{
        background-image: url("../assets/img/footer-bg.jpg");
    }

    .footer-top .container{
        display: flex;
    }

    ul{
        color: white;
        list-style: none;
        padding: 15px 50px 0 0;
    }

    ol{
        font-weight: bold;
        font-size: 22px;
        text-transform: uppercase;
        padding-bottom: 10px;
    }

    li a{
        display: block;
        text-decoration: none;
        color: grey;
    }

    li a:hover{
        color: white;

    }

</style>