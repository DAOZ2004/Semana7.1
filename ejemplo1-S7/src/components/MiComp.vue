
<!--JS-->>
<script setup>
  import {ref} from 'vue';
  var Contador = ref(0);

  var aumentar = () =>{
    Contador.value++;
  }

</script>


<!--HTML-->>
<template>

   <div class="caja">

    <h1>Hola mundo, estoy en vue</h1>

    <button @click="aumentar">Presiona aqui</button>
    <p>Haz hecho click {{ Contador }} veces</p>
   </div>

</template>


<!--CSS-->
<style scoped>
  .caja{
    border: 2px solid maroon;
    border-radius: 8 px;
    /*text-align: center;*/
    padding: 20px;
  }

  button{
    background-color: rgb(0, 15, 128);
    border-radius: 8px;
    cursor: pointer;
    padding: 10px 20px;
  }


</style>