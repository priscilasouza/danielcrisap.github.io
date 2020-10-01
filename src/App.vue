<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" width="25%" /> -->
    <HelloWorld msg="Daniel Cristian" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import ReachMe from "./components/ReachMe";

export default {
  name: "App",
  components: {
    ReachMe,
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
