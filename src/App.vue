<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Seat name="姓名1" v-bind:score="12"></Seat>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Seat from './components/Seat.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Seat
    
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
