<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  created() {
    document.body.removeChild(document.getElementById('appLoading'));
   
  }
}
</script>

<style>
@import "./assets/css/reset.css";
@import "./assets/font/iconfont.css";

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
