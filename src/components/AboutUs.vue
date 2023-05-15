<template>
    <div id="about-us">
        <div class="strategy">

            <div class="l-side">
                <img src="/images/business-people-working-together-on-project-and-5FHSKBL.jpg" alt="">
            </div>

            <div class="r-side">
                <hr>
                <span>about us</span>
                <h2>we make your strategy work</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis autem a officia possimus praesentium quaerat fugit suscipit amet pariatur minus ex deleniti corporis officiis aliquam exercitationem culpa, labore dolore perferendis.</p>
            </div>
        </div>

        <div class="get-started">
            <div>
                <h3>we help to deliver the business case</h3>
            </div>
            <div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe mollitia, perferendis ratione possimus aperiam, at iure adipisci excepturi dolor nobis deserunt facilis. Itaque, repellat. Fuga animi velit beatae harum tempora!</p>
            </div>
            <div>
                <button>get started</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AboutUs'
}
</script>

<style scoped>
    #about-us{
        background-color: var(--bg-color);
    }
    .strategy{
        display: flex;
        align-items: center;
        color: white;
    }
    .strategy .l-side{
        width: 60%;
    }
    .strategy .l-side img{
        height: 750px;
        display: block;
    }
    .strategy .r-side{
        width: 30%;
        text-transform: uppercase;
    }
    .strategy .r-side hr{
        width: 30px;
        border-color: var(--celeste);
        display: inline-block;
        margin-right: 10px;
    }
    .strategy .r-side h2{
        font-size: 3rem;
        line-height: 3rem;
        margin: 20px 0;
    }
    .strategy .r-side p{
        text-transform: none;
    }

    .get-started{
        width: 90%;
        height: 250px;
        background-color: var(--celeste);
        display: flex;
        justify-content: space-between;
        align-items: center;
        
    }
    .get-started :first-child{
        flex-basis: 30%;
        margin-left: 70px;
    }
    .get-started div:nth-child(2){
        flex-basis: 50%;
    }
    
    .get-started h3{
        font-size: 2rem;
        line-height: 2rem;
        text-transform: uppercase;
    }
    .get-started div:last-child{
        align-self: flex-end;
    }
    .get-started button{
        background-color: var(--text-red);
        text-transform: uppercase;
        color: white;
        border: transparent;
        padding: 15px 30px;
        cursor: pointer;
    }
</style>