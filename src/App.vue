<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <clock></clock>
    <nock></nock>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import VueClock from 'vue-clock'

const { Clock, Nock } = VueClock

export default {
  name: 'app',
  components: {
    HelloWorld,
    Clock,
    Nock
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
