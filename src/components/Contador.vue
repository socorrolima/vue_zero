
<script setup>

import {ref} from 'vue';

const Contador = ref(0);

const incrementar = () =>{
  Contador.value++;
}

const decrementar = () =>{
  Contador.value--;
}

</script>


<template>

  {{ Contador }}<br><br>
  <button @click="incrementar">Incrementar</button><br><br>
  <button @click="decrementar">Decrementar</button>

</template>


<style scoped>

</style>
