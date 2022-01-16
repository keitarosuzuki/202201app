<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Pomodoro />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import Pomodoro from '../node_modules/vuemodoro/src/Pomodoro.vue';

export default {
  name: 'App',
  components: {
    Pomodoro,
    // HelloWorld
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
