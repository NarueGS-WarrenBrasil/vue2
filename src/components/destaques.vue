<template>
    <div class="destaques">
        <div >
            <img id="moça" loading="lazy" src="https://warren.com.br/assets/images/modules/produtos/d_carteiras.jpg" width="645" height="728" alt="foto Carteiras - warren">
            <div class="texto1">
                <h1 id="title1">Tá consado de Loren ipsum?</h1>
                <h3>Então vem pra Warren!<br>Aqui te impulsionamos pra <strong>bem longe</strong> do velho<br>Lorem ipsum etiam congue
                 <br>hac blandit class duis, aliquam<br>
                 donec gravida sagittis sollicitudin primis<br> 
                 pulvinar, egestas tincidunt lacus suscipit <br>nibh senectus. ultricies leo aliquet<br> 
                 potenti dolor mauris<br> eu arcu etiam habitasse<br> 
                 pulvinar, in netus pretium <br>elementum scelerisque potenti 
                 <br>urna sagittis id, curae conubia etiam <br> </h3>
                 <BotaoM id="b"/>
            </div>
            
        </div>

        <img id="moço" loading="lazy" src="https://warren.com.br/assets/images/modules/produtos/d_bolsa.jpg" width="645" height="728" alt="foto Carteiras - warren">
        <div class="texto2">
                <h1 id="title2">Tá consado de Loren ipsum?</h1>
                <h3>Então vem pra Warren!<br>Aqui te impulsionamos pra <strong>bem longe</strong> do velho<br>Lorem ipsum etiam congue
                 <br>hac blandit class duis, aliquam<br>
                 donec gravida sagittis <h3 id="borda">elementum scelerisque potenti 
                 <br>urna sagittis id, curae conubia etiam </h3> 
                 <h3> primis
                 pulvinar, egestas tincidunt lacus suscipit <br>nibh senectus. ultricies leo aliquet<br> 
                 potenti dolor mauris<br> eu arcu etiam habitasse<br> 
                 pulvinar, in netus pretium <br></h3></h3>
                 <BotaoM id="b"/>
            </div>
    </div>
</template>

<script>
    import BotaoM from "./B/BotaoM.vue"
    export default {
        name:'destaques',
        components:{
            BotaoM
        }
        
    }
</script>

<style scoped>

    .destaques{
        background: white;
        margin-top:45%;
        min-height: 1700px;
        padding: 1px;
    }

    #moça{
        margin: 2.5% 10%;
        margin-right: 0%;
        
    }
    
    .texto1{
        float: right;
        margin: 2.5% 10%;
        margin-left: 0%;
        font-size: 150%;
    }

    #b{
        font-size: 200%;
        padding: 5px;
        display: inline-block;
          
    }

    .texto2{
        float:left;
        
        margin-left: 10%;
        font-size: 150%;
    }

    #moço{
        float: right;
        margin: 0% 12%;
        margin-left: 0%;
    }
    #borda{
        border-bottom: solid 2px rgb(255, 0, 98);
        
    }

</style>