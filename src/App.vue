<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App" mensaje="props in vue"/>
  <!--<PropsModal /> -->


  <!--<button class="btn btn-success">Abrir Modal</button> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
/*import PropsModal from './components/PropsModal.vue' */


export default {
  name: 'App',
  components: {
    HelloWorld,
    /* PropsModal */
  },
  
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
