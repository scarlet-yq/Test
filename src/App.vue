<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Search></Search>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Search from './components/search.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Search
  }
}
</script>

<style lang="less">
@color: red;
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: @color;
  margin-top: 60px;
}
</style>
