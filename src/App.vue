<template>
  <img alt="Vue logo" src="./assets/logo.png" />

  <TestApp />
</template>

<script>
import TestApp from "./components/TestApp.vue";

export default {
  name: "App",
  components: { TestApp },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
