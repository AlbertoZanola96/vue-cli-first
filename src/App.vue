<template>
  <div id="app">
    <CliFirst />
    <hero />
  </div>
</template>

<script>
import CliFirst from './components/CliFirst.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    CliFirst,
    hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>