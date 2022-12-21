<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Hola from './components/Hola.vue'
</script>

<template>
  <div id="app">
    <h1>La meva app</h1>
    <Hola nom="David"></Hola>
    <router-view />
  </div>
</template>

<style scoped>

</style>

