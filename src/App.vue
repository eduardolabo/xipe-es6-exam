<template>
  <img alt="Vue logo" src="./assets/Xipe-logo_Black.svg">
  <h1>Here is where you shine</h1>
  <input type="text" :="inputString"/>
  <HelloWorld msg="Vue.js"/>
  </template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'App',
  components: {
    HelloWorld
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
img{
  height: 150px;
}
</style>
