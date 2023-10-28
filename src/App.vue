<template>
  <div id="app">
    <Nav /> 
    <Main />
    <Foot />

    <router-view></router-view>
  </div>
</template>

<script>
/* eslint-disable */
// eslint-disable-next-line
import Nav from "@/components/Nav.vue"; // Updated component name
import Main from "@/components/Main.vue"; // Updated component name
import Foot from "@/components/Foot.vue"; // Updated component name

export default {
  name: "App",
  components: {
    Foot,
    Main,
    Nav
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
