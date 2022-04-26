<template>
    <div class="investimento">
        <h1 id="title">Investir é sobre você<br> <p id="detalhe">começe a investir em poucos minutos. descomplique</p></h1>
        
        <ButtonB id="b"/>
    </div>
</template>

<script>
    import ButtonB from "./B/BotaoB.vue"
    export default {
        name:'Investir',
        components:{
            ButtonB
        }
    }
</script>

<style scoped>
    div{
        background-color: rgb(164, 161, 161);
        display: flex;
        margin-bottom: 5%;
        width: 100%;
        
        
    }
    #detalhe{
        font-size: 50%;
    }

    #title{
        margin: 5% 10%;
        margin-top: 3%;
        color: azure;
        font-size: 250%;
    }
    #b{
        font-size: 295%;
        display: inline-block;
        margin-top: 2%
    }
    .investimento{
        display: flex;
        justify-content: space-around;
    }
</style>