<template>
  <div id="app">
    <h2>ehanced-resolve example</h2>
    <hello-world />
  </div>
</template>

<script>
import HelloWorld from 'theme/Hello.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
  },
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
