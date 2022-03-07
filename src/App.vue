<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myFirstTitle />
  </div>
</template>

<script>
import myFirstTitle from './components/myFirstTitle.vue'

export default {
  name: 'App',
  components: {
    myFirstTitle
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
