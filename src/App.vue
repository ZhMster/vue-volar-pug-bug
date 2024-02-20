<template lang="pug">
img(alt="Vue logo" src="./assets/logo.png")/
HelloWorld(msg="Hello Vue 3 + TypeScript + Vite")/
div Try {{autoc}} this with your editor [vscode]: {{data}}/
</template>

<script lang="ts" setup>
import HelloWorld from './components/HelloWorld.vue'
import { ref } from 'vue';

const autoc = "autocomplete"
const dataTest = ref("And Pug")
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
