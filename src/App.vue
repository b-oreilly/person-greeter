<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <PersonGreeter/>
  </div>
</template>

<script>
import PersonGreeter from '@/components/PersonGreeter.vue'

export default {
  name: 'App',
  components: {
    PersonGreeter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #313131;
  margin-top: 60px;
}
</style>
