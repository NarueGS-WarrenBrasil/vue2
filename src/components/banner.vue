<template>
    <div class="banner">
        <h1>Quer investir seu dinheiro?<br>
            
            Abra sua conta.<br>É grátis.
        </h1>
        <p class='tes'>Clique aqui para ter saber por onde começar</p>
        <BotaoB id="banner_b"/>
        
    </div>
</template>

<script>
    import BotaoB from './B/BotaoB.vue'
    export default {
        name:"banner",
        components:{
            BotaoB,
        }
    }
</script>

<style scoped>
    
    .banner{
        float: left;
        min-width: 50%;
        max-width: 100%;
        min-height: 500px;
        max-height: 750px;
        font-size: 300%;
        color:azure;
        margin-left: 5%;
    }

    #banner_b{
        font-size: 95%;
        display: inline-block;
        margin-top: 6%;        
    }
    
    
    
    
</style>

