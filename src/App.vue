<template>
  <div id="app">
    <router-view></router-view>
   <!-- <router-link to="/Nav">Nav</router-link>-->
  </div>
</template>

<script>
export default {
  name: 'app'
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
#app{
  height:100%;
  width:100%;
  margin:0;
}
body{
  margin:0;
  padding:0;
}
</style>
