<template>
    <div id="blog">
        <div class="container">
            <hr>
            <span>blog</span>
            <div class="title-cards">
                <h2>the recent you must read it</h2>
                <button>view all</button>
            </div>
            <div class="cards">
                <div class="card">
                    <img src="/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg" alt="">
                    <div class="info">
                        <span>july 4, 2019</span>
                        <span>by paul</span>
                        <h3>Canadian Consulting Firm acquired by UK Giant</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis asperiores rerum cupiditate officiis provident</p>
                    </div>
                </div>

                <div class="card">
                    <img src="/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg" alt="">
                    <div class="info">
                        <span>july 4, 2019</span>
                        <span>by paul</span>
                        <h3>Canadian Consulting Firm acquired by UK Giant</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis asperiores rerum cupiditate officiis provident</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BlogComp'
}
</script>

<style scoped>
#blog{
    background-color: var(--bg-color);
    padding: 6rem 0;
}
    .container{
        width: 85%;
        margin: 0 auto;
        text-transform: uppercase;
        color: white;
    }
    .container hr{
        display: inline-block;
        width: 30px;
        margin-right: 10px;
        border-color: var(--celeste);
    }
    .cards, .title-cards{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 10px;
    }
    .card{
        width: calc(100% / 2 - 15px);
        position: relative;
    }
    .card img{
        width: 100%;
        display: block;
    }
    .info{
        width: 70%;
        position: absolute;
        right: 0;
        top: 320px;
        padding: 40px 70px;
        background-color: white;
        color: black;
        text-transform: none;
    }
    .info span{
        margin-right: 10px;
        color: red;
    }
    .info h3{
        margin-bottom: 10px;
        margin-top: 10px    ;
    }
    .title-cards button{
        text-transform: uppercase;
        background-color: var(--celeste);
        border: transparent;
        padding: 10px 20px;
        cursor: pointer;
    }
</style>