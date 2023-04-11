<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="hello"/>
  <GoHome msg="집에 가자"/>
  <GoStop/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import GoHome from './components/GoHome.vue';
import GoStop from './components/GoStop.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    GoHome,
    GoStop
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
