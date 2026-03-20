<script setup>

import { ref } from 'vue';

   var Nombre = ref('DAOZ');
   var Edad = 21;
   var universidad = "UGB";
   var carrera = "Ing. en sistemas";

</script>


<template>
    <div>
        <h1>Perfil</h1>
        <h2>{{ Nombre }}</h2>
        <p>Edad: {{ Edad }}</p>
        <p>Universidad: {{ universidad }}</p>
        <p>Carrera: {{ carrera }}</p>
    </div>


</template>


<style scoped>


</style>