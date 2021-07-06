<template>
    <div class="jumbo">
        <!-- sono un jumbo -->
        <div class="img_wrap">
            <img src="../assets/jumboImg.jpg" alt="img jumbo">
            <p>Sono un Jumbotron!!!!! E i nani sono stati catturati!</p>
        </div>
    </div>
</template>

<script>
    export default {
        name:'Hero',
        props:{
            //nomeVariabile : tipo(string,bool,int,float ....)
        },
    }
</script>

<style scoped>
    .jumbo{
        /* background-color: lightblue; */
        height: 600px;

    }
    .img_wrap{
        position: relative;
        height: 100%;
    }
    img{
        height: 100%;
    }
    p{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50% , -50%);
        color: white;
        font-size: 3rem;
    }
</style>