<template>
  <div id="app">
    <LearnJava msg="Welcome to Your Vue.js App Okela"/>
  </div>
</template>

<script>
import LearnJava from './components/LearnJava.vue'

export default {
  name: 'App',
  components: {
    LearnJava
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
