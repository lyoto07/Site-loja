<template>
    <h2>Nossos Serviços</h2>
    <div class="fundo">

    </div>
    <div class="card">
            teste 123
        </div>
  </template>
<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
    name: 'cardCard'
});
</script>
  <style>
  .fundo{
    position: relative;
    width: 343px;
    height: 104px;
    margin: 0 16px;
    background: #FFB100;
    border-radius: 15px;

  }

  .card{
    position: absolute;
    width: 100px;
    height: 100px;
    left: 138px;
    top: 504px;

    background: #F5F5F5;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
  }
  </style>
  