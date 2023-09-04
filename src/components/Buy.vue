<template>

    <form class="ativoBuy">
        <h2>Compra de Ativo</h2>
        <input type="text" id="buyAtivo" name="buyAtivo" disabled>
        <h4>Valor total do ativo: R$0,00</h4>

        <div class="quantvalBuy">
            <div class="valorBuy">
                <h3>Quantidade</h3>
                <input type="number" placeholder="0" required> 
            </div>    
            <div class="valorOrder">
                <h3>Valor da ordem</h3>
                <h2>R$0,00</h2>
            </div>
            
        </div>
        <button class="large" id="buyButton">Confirmar</button>
        <button type="button" id="cancelButton" name="cancelButton">Cancelar</button>         
    </form>
    
</template>

<script>

    export default {
        name: 'Buy',
        data(){
            return {
                
            }
        }

    }

</script>