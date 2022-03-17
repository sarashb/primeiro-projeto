<template>
  <div id="app">
      <ExemploContador/>
  </div>
</template>

<script>
import ExemploContador from './components/ExemploContador'

export default {
  name: 'App',
  components: {
    ExemploContador
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
