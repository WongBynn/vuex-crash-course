<template>
  <div id="app">
    <ToDos />
  </div>
</template>

<script>
import ToDos from "./components/ToDos";
import store from './store/store'

export default {
  name: "app",
  store,
  components: {
    ToDos
  }
};
</script>

<style>

body{
  background:#66CDAA;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  width: 1100px;
  height: 60px;
  margin: 60px auto;
}
h3{
  padding: 10px;
  margin:0;
}
</style>
