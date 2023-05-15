<template>
    <div id="project">
        <div class="container">
            <hr>
            <span>project</span>

            <div class="title">
                <h2>our expert trusted consultants help clients</h2>
                <div>
                    <i class="fa-solid fa-arrow-left"></i>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </div>
            <div class="images">
                <img src="/images/DRY-1-790x592.jpg" alt="project-1">
                <img src="/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg" alt="project-2">
                <img src="/images/z1el4c4p-790x592.jpg" alt="project-3">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ProjectCom'
}
</script>

<style scoped>
    #project{
        background-color: var(--bg-color);
    }
    #project .container{
        width: 85%;
        margin: 0 auto;
        padding: 40px 0;
        color: white;
    }
    #project .container hr{
        width: 30px;
        margin-right: 10px;
        border-color: var(--celeste);
        display: inline-block;
    }
    #project .container span{
        text-transform: uppercase;
    }
    .title h2{
        font-size: 2rem;
        line-height: 2rem;
        text-transform: uppercase;
        margin: 20px 0;
    }
    .title{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .title .fa-solid{
        background-color: #36354C;
        height: 40px;
        width: 40px;
        line-height: 40px;
        text-align: center;
        cursor: pointer;
    }
    .fa-arrow-left{
        margin-right: 5px;
    }
    .images{
        display: flex;
        justify-content: space-between;
    }
    .images img{
        width: calc(100% / 3 - 1%);
        margin-top: 20px;
    }
</style>