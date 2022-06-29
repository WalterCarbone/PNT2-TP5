<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
  import Home from './componentes/Home.vue'
  export default {
    name: 'App',
    components: {
      Home
    }
  }
</script>

<style>
  
  body {
    background: #232323;
    margin: 0;
    font-family: "Montserrat", "Avenir";
  }
  h1 {
    font-weight: normal;
    line-height: 1.1;
    padding: 20px 0;
  }
</style>