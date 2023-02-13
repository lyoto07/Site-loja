<template>
  <menu1/>
  <cabecalho/>
  <cardCard/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import menu1 from './Menu.vue'
import cabecalho from './cabecalho.vue'
import cardCard from './card.vue'

export default defineComponent({
  name: 'HelloWorld',
  components:{
    menu1,
    cabecalho,
    cardCard
  } 
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
