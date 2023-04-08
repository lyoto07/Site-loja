<template>
  <Conteudo msg="Welcome to Your Vue.js + TypeScript App"/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Conteudo from './components/Conteudo.vue';
export default defineComponent({
  name: 'App',
  components: {
    Conteudo
  }
});
</script>

<style>
</style>
