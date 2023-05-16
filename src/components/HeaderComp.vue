<template>
    <header>
        <div class="container">
            <hr>
            <span>always the best way you need it</span>
            <h1>the best business consulting</h1>
            <button>read more</button>
            <div class="circle">
                <i class="fa-solid fa-play"></i>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: 'HeaderComp'
}
</script>
<style scoped>
    header{
        height: 750px;
        background-color: var(--bg-color);
        background-image: url('/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg');
        background-repeat: no-repeat;
        background-position: right;
        color: white;
        text-transform: uppercase;
        display: flex;
        align-items: center;
    }
    .container{
        margin-left: 150px;
        width: 20%;
        line-height: 4rem;
    }
    .container hr{
        width: 30px;
        border-color: var(--celeste);
        display: inline-block;
        margin-right: 10px;
    }
    .container h1{
        font-size: 4rem;
    }
    .container button{
        background-color: var(--celeste);
        text-transform: uppercase;
        padding: 12px 30px;
        border: transparent;
        cursor: pointer;
    }
    .container button:hover{
        background-color: var(--text-red);
        color: white;
        transition: ease-in-out 0.2s;
    }
    .fa-play{
        color: var(--celeste);
    }
    .circle{
        display: inline-block;
        vertical-align: middle;
        margin-left: 30px;
        border: 1px solid white;
        height: 40px;
        width: 40px;
        line-height: 40px;
        text-align: center;
        border-radius: 50%;
        cursor: pointer;
    }
</style>