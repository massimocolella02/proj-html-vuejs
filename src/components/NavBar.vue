<template>
    <nav>
        <div class="container">
            <div class="l-side">
                <img src="/images/logotype.png" alt="logo">
            </div>
            <div class="r-side">
                <ul>
                    <li>
                        <a href="">home</a>
                    </li>
                    <li>
                        <a href="">about</a>
                    </li>
                    <li>
                        <a href="">projects</a>
                    </li>
                    <li>
                        <a href="">services</a>
                    </li>
                    <li>
                        <a href="">blog</a>
                    </li>
                    <li>
                        <a href="">contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style scoped>
nav{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
}
nav .container{
    width: 90%;
    height: 60px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav ul{
    display: flex;
}
nav ul li{
    margin-right: 15px;
    line-height: 60px;
}
nav ul li a{
    text-transform: uppercase;
    color: #aaaaaa;
}
nav ul li:hover a{
    color: white;
}
nav ul li:hover{
    border-top: 2px solid white;
}
.l-side img{
    height: 20px;
}
</style>