<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <first msg="First component"/>
</template>

<script>
import first from './components/first.vue'
export default {
  name: 'App',
  components: {
    first
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
