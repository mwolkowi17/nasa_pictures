<template>
  <div id="app">
    <img src="./assets/logo.png">
    <search></search>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Search from './components/Search'
import axios from 'axios'
export default {
  name: 'App',
  components: {
    Search
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
