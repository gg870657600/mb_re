<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  import user from "./components/user";
export default {
  name: 'App',
  components:{
    "user":user
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* //text-align: center; */
  /* //color: #2c3e50; */
  /* //margin-top: 60px; */
  list-style:none;
  
}
body{
  background-color: #444444;
  width:100%;
  height:100%
}
</style>
