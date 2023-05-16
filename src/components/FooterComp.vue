<template>
    <footer>
        <div class="container">
            <div class="footer-up">
                <a href="#">
                    <img src="/images/logotype-2-139x23.png" alt="">
                </a>

                <ul class="list-page">
                    <li>
                        <a href="#">home</a>
                    </li>
                    <li>
                        <a href="#">about</a>
                    </li>
                    <li>
                        <a href="#">projects</a>
                    </li>
                    <li>
                        <a href="#">services</a>
                    </li>
                    <li>
                        <a href="#">blog</a>
                    </li>
                    <li>
                        <a href="#">contact</a>
                    </li>
                </ul>

                <ul class="list-social">
                    <li>
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    </li>
                    <li>
                        <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
                    </li>
                    <li>
                        <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                    </li>
                    <li>
                        <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    </li>
                </ul>
            </div>
            <hr>
            <div class="footer-down">
                <div>
                    <a href="" class="d-block">Terms of use</a>
                    <a href="">Privacy Environmental Policy</a>
                </div>
                <a href="">Copyright <i class="fa-regular fa-copyright"></i> 2020 Phlox Consulting. All Rights Reserved.</a>

                <div class="icon">
                    <a href="#"><i class="fa-solid fa-arrow-up"></i></a>
                    <button><i class="fa-regular fa-comment"></i></button>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterComp'
}
</script>

<style scoped>
.d-block{
    display: block;
}
    footer{
        background-color: var(--bg-color);
        padding: 80px 0;
    }
    .container{
        width: 85%;
        margin: 0 auto;
    }
    .footer-up{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    ul{
        display: flex;
    }
    ul li{
        margin-right: 20px;
        text-transform: uppercase;
    }
    .list-page li a{
        color: #727283;
    }
    .list-page li a:hover{
        color: white;
    }
    .list-social li a{
        color: white;
    }
    hr{
        margin: 40px 0;
        border-color: #727283;
    }
    .footer-down{
        color: #727283;
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: relative;
    }
    .footer-down a{
        color: #727283;
    }
    .icon{
        position: absolute;
        left: 102%;
        display: flex;
        align-items: center;
    }
    .fa-arrow-up{
        display: inline-block;
        width: 30px;
        height: 30px;
        text-align: center;
        line-height: 30px;
        background-color: white;
        border-radius: 50%;
        margin-right: 10px;
    }
    .icon button{
        background-color: #527CEB;
        color: white;
        height: 40px;
        width: 40px;
        line-height: 40px;
        text-align: center;
        border: transparent;
        border-radius: 50%;
        font-size: 1.2rem;
        cursor: pointer;
    }
</style>