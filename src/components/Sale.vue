<template>

    <form class="ativoSale" method="POST">

        <h2>Venda de Ativo</h2>
        <input type="text" id="saleAtivo" name="saleAtivo" disabled>
        <h4>Valor total do ativo: R$0,00</h4>

        <div class="quantvalSale">
            <div class="valorBuy">
                <h3>Quantidade</h3>
                <input type="number" placeholder="0" required> 
            </div>    
            <div class="valororderSale">
                <h3>Valor da ordem</h3>
                <h2>R$0,00</h2>
            </div>
            
        </div>
        <button class="large" id="buyButton">Confirmar</button>
        <button type="button" id="cancelButton" name="cancelButton" v-on:click="limparForm();">Cancelar </button>      
    </form>
    
</template>

<script>

    export default {
        name: 'Sale',
        data(){
            return {
                
            }
        }


    }
    

</script>