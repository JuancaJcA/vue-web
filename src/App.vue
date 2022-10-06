<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="https://lpz.ucb.edu.bo/wp-content/uploads/2021/12/Colores-Vertical-3.png"
    />
    <HelloWorld msg="Proyecto de Tecno Web" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
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
