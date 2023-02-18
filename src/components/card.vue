<template>
  <div class="d-flex justify-content-center title">
    <h2>Nossos Serviços</h2>
  </div>
    <div class="fundo">
      <div class="cards">
        <div class="card1"></div>
        <div class="card1"></div>
        <div class="card1"></div>
      </div>
    </div>

  </template>
<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
    name: 'cardCard'
});
</script>
<style>
  .title{
    margin: 57px 0 20px 0;
  }
  .fundo{
    position: relative !important;
    width: 343px;
    height: 104px;
    margin: 0 16px;
    background: #FFB100;
    border-radius: 15px;

  }
  
  .cards{
    width: 100%;
    display: flex;
    position: absolute;
    top: -17px;
    justify-content: space-evenly;
  }

  .card1{
    width: 100px;
    height: 100px;
    background: #e4e4e4;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
  }
</style>
  