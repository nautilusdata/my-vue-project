<script setup>
import HeaderComponent from "./components/HeaderComponent.vue"
import { ref } from 'vue';

    let number = ref(0);
    setInterval(()=>{
      number.value++;
    }, 1000);
</script>


<template>
  <HeaderComponent></HeaderComponent>
  <h1 class="title">Hola a todos!</h1>
  <h2>{{  number }}</h2>
</template>


<style></style>

