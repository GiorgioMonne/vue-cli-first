<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Eserc/>
  </div>
</template>

<script>
import Eserc from './components/Eserc.vue';

export default {
  name: 'App',
  components: {
    Eserc
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
