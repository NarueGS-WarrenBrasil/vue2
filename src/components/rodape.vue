<template>
    <div>
        <ol class='dowBox'>
            <ol>
                <h1>Sobre</h1>
                <li>Sobre a Warren</li><br>
                <li>Quanto Custa</li><br>
                <li>Warren Magazine</li><br>
                <li>Trabalhe Conosco</li><br>
                <li>Imprensa</li>

            </ol><br>
             <ol>
                 <h1>Produtos</h1>
                <li>Bolsa</li><br>
                <li>Carteiras</li><br>
                <li>Home Broker</li><br>
                <li>Produtos de Investimento</li><br>
                <li>Previdência</li><br>
                <li>Conta PJ</li><br>
                <li>Warren Pro</li><br>
            </ol><br>
             <ol>
                 <h1>Escritórios</h1>
                <li>Blumenau </li><br>
                <li>Curitiba</li><br>
                <li>Florianópolis</li><br>
                <li>Itajaí </li><br>
                <li>Jaraguá do Sul </li><br>
                <li>Joinville</li><br>
                <li>Porto Alegre </li><br>
                <li>Rio de Janeiro </li><br>
                <li>São Paulo </li><br>
            </ol>
            <ol>
                 <h1>Fale Conosco</h1>
                 <li class="fraco">Dúvidas?</li>
                <li>Acesse nosso FAQ</li><br>
                <li class="fraco">Precisa de ajuda?</li><br>
                <li>meajuda@warren.com.br</li><br>
                <li class="fraco">Acesse o chat</li><br>
                <li>Das 8h às 20h (dias úteis)</li><br>
                <li class="fraco">Acesse o WhatsApp</li><br>
                <li>Das 9h às 18h (dias úteis)</li><br>
                










                
        
            </ol>
        </ol>
    </div>
</template>

<script>
    export default {
        name:'rodape'
    }
</script>

<style scoped>
    .dowBox{
        display: flex;
        justify-content:space-around;
        margin-bottom: 5%;
    }
    ol {
        
        color: whitesmoke;
    }
    h1{
        font-size: 300%;
    }
    ol li{
        
        list-style: none;
        margin-left: 1%;
        color: whitesmoke;
        font-size: 200%;
    }
    .fraco{
        color:rgb(196, 193, 193)
    }
</style>