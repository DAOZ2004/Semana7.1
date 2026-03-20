<script setup>
   import {ref} from 'vue';

   var input1 = ref(null)
   
   var Valor = ref('')

   var texto = ref('')

   var mostrarValor = () =>{
     Valor.value = input1.value.value;
   }

</script>


<template>
    

    <p>Escribiste: {{ texto }}</p>

    <input type="text" placeholder="Escribe aqui">
   
    <input type="text" ref="input1" v-model="texto" placeholder="Escribe">

   <button @click="mostrarValor">Click</button>

   <p>Esto pusiste: {{ Valor }}</p>

</template>


<style scoped>


</style>