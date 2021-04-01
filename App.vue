<template>
  <div id="app">
    <Trucks />
  </div>
</template>

<script>
import Trucks from './components/Trucks.vue'

export default {
  name: 'App',
  components: {
    Trucks
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
