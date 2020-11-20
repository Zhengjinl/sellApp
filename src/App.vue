<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <h1>{{ msg }}</h1>
    <h2>1111</h2>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      'msg': '第一个app'
    }
  }
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
