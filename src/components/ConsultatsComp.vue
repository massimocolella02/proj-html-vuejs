<template>
    <div id="consultants">
        <div class="container">
            <h2>our consultants con help you</h2>
            <hr>
            <div class="container paragraph">
                <div class="item" v-for="(elem, index) in arrayConsultants" :key="index">

                    <div class="icon">
                        <i :class="elem.icon"></i>
                    </div>

                    <div class="info">
                        <h3>{{ elem.title }}</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint hic facilis quidem debitis aspernatur mollitia repellendus sapiente earum enim? Dolorem corporis officiis iste eligendi delectus sequi dignissimos ducimus enim optio?</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ConsultatsComp',
    data() {
        return {
            arrayConsultants: [
                {
                    title: 'statistical consulting',
                    icon: "lni lni-stats-up"
                },
                {
                    title: 'digital consulting',
                    icon: "fa-solid fa-bullhorn"
                },
                {
                    title: 'banking consulting',
                    icon: "lni lni-wallet"
                },
                {
                    title: 'enterprise consulting',
                    icon: "fa-solid fa-bullseye"
                }
            ]
        }
    },
}
</script>

<style scoped>
#consultants{
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    padding: 50px 0;
}
    .container{
        width: 80%;
        text-transform: uppercase;
    }
    h2{
        display: inline;
        vertical-align: middle;
    }
    hr{
        border: 1px solid var(--celeste);
        display: inline-block;
        margin-left: 15px;
        width: calc(100% - 15px - 25.5pc);
        vertical-align: middle;
    }
    .paragraph{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    .item{
        flex-basis: 40%;
        display: flex;
        padding: 40px 0;
    }
    .lni, .fa-solid{
        border: 1px solid var(--text-red);
        background-color: var(--text-red);
        color: white;
        height: 40px;
        width: 40px;
        line-height: 40px;
        text-align: center;
        border-radius: 50%;
        margin-right: 20px;
    }
    .info p{
        text-transform:none;
    }
</style>