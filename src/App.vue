<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <InicioSesion/>
  <InicioSesionIf></InicioSesionIf>
  <FrutasFor></FrutasFor>
 
</template>

<script>

import InicioSesion from './components/InicioSesion.vue';
import InicioSesionIf from './components/InicioSesionIf.vue';
import FrutasFor from './components/FrutasFor.vue';

export default {
  name: 'App',
  components: {
    InicioSesion,
    InicioSesionIf,
    FrutasFor
}
}
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
