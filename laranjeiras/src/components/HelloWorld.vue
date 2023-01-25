<template>
  <menu1></menu1>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import menu1 from '../components/menu.vue'

export default defineComponent({
  name: 'HelloWorld',
  components:{
    menu1
  } 
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
