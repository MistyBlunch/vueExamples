<template>
  <div id="app">
  <Char />
  </div>
</template>

<script>
import Char from './components/Char.vue'

export default {
  name: 'app',
  components: {
    Char
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
