<script setup>
import { ref } from "vue";
const number = ref(1);

const addOne = () => {
  number.value++;
}
</script>

<template>
  <h1>Hola a todos!</h1>
  <h2 @click="addOne">{{  number }}</h2>
</template>

<style>
h1 {
    color: red;
}
h2 {
  color: rgb(9, 0, 128);
}
</style>

