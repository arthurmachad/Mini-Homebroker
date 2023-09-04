<template>

    
    <form class="ativHome" name="formulario">
            <h1>Mini Homebroker</h1> <br>       
        
        <div class="ativoHome">
            <input type="text" name="ativo" placeholder="Ativo" v-model="ativo" required>
            <button class="large" id="buyButton">Comprar</button>
            <button class="large" id="saleButton" >Vender</button>
            <button class="large" id="searchButton">Pesquisar</button>
        </div>
    </form>
    
</template>


<script>
import { normalizeClass } from 'vue'

    export default {
        name: 'Home',
        data(){
            return {
            }
        },

        methods: {
        }
    }


</script>

<style>

</style>