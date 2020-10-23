<template>
  <div id="app">
    <NavBar/>
    <Jumbotron/>
    <CloudInfo/>
    <Features/>
    <Technology/>
  </div>
</template>

<script>

import NavBar from './components/NavBar.vue'
import Jumbotron from './components/Jumbotron.vue'
import CloudInfo from './components/CloudInfo.vue'
import Features from './components/Features.vue'
import Technology from './components/Technology.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    Jumbotron,
    CloudInfo,
    Features,
    Technology,
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
