<template>
    <div id="testimonial">
        <div class="title">
            <span>testimonials</span>
            <div>
                <hr>
            </div>
        </div>
        <div class="info">
            <h2>what's the customer say about our work</h2>
        </div>
        <div class="recensioni">
            <div class="item" v-for="(elem, index) in 3" :key="index">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem pariatur, porro unde suscipit mollitia commodi ad dolore iusto repellendus reprehenderit repellat, ratione aliquam explicabo laborum rerum itaque, consectetur ab dignissimos!</p>
                <h4>Vera Duncan</h4>
                <span>Amazon Inc.</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    #testimonial{
        background-color: var(--bg-color);
        position: relative;
        padding: 50px 0; 
    }
    .title{
        width: 85%;
        margin: 0 auto;
        color: white;
        text-transform: uppercase;
        display: flex;
        justify-content: center;
        position: relative;
    }
    .title hr{
        display: inline-block;
        border-color: var(--celeste);
        width: 30px;
    }
    .title div{
        position: absolute;
        right: 0;
    }
    .info{
        width: 85%;
        margin: 0 auto;
        color: white;
        margin-top: 15px;
    }
    .info h2{
        text-align: end;
        text-transform: uppercase;
        font-size: 2rem;
        line-height: 2rem;
    }
    .recensioni{
        width: 85%;
        margin-left: auto;
        margin-top: 20px;
        display: flex;
        justify-content: space-around;
        background-color: white;
        padding: 30px;
    }
    .item{
        flex-basis: calc(100% / 3 - 3%);
        color: #888888;
    }
    .item h4{
        margin-top: 30px;
        color: black;
    }
</style>