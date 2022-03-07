<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myFirstTitle />
    <hr>
    <myFirstJumbo />
  </div>
</template>

<script>
import myFirstTitle from './components/myFirstTitle.vue'
import myFirstJumbo from './components/myFirstJumbo.vue'

export default {
  name: 'App',
  components: {
    myFirstTitle,
    myFirstJumbo
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
