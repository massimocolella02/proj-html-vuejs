<template>
    <div id="talk-about-work">
        <div>
            <h2>let's talk about work</h2>
            <p>A wonderful serenity has taken possession Far far away, behind the word mountains.</p>
            <button>get started</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TalkAboutWork'
}
</script>

<style scoped>
    #talk-about-work{
        height: 400px;
        background-image: url('/images/business-people-working-together-on-project-and-B3MZ4TX.jpg');
        background-repeat: no-repeat;
    }
    #talk-about-work{
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        text-align: center;
    }
    h2{
        text-transform: uppercase;
        margin-bottom: 10px;
        font-size: 2rem;
    }
    p{
        margin-bottom: 10px;
    }
    button{
        border: transparent;
        background-color: var(--bg-color);
        text-transform: uppercase;
        color: white;
        padding: 10px 25px;
        cursor: pointer;
        
    }
</style>