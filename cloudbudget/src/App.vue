<template>
  <div id="app">
    <NavBar/>
    <Jumbotron/>
  </div>
</template>

<script>

import NavBar from './components/NavBar.vue'
import Jumbotron from './components/Jumbotron.vue'



export default {
  name: 'App',
  components: {
    NavBar,
    Jumbotron,
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
