<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Search></Search>
    <Type></Type>
    <h4>this is app page</h4>
    <h5>看看是否有冲突,最好由冲突</h5>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Search from './components/search.vue'
import Type from './components/type.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Search,
    Type
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
