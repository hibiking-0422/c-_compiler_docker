<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to c++ complier!"/>
    <Compiler />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Compiler from './components/Compiler.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Compiler
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
