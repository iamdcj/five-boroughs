<template>
  <div id="app">
    <Landing msg="Welcome to the Five Boroughs of NYC" />
  </div>
</template>

<script>
import Landing from "./components/landing/Landing.vue";

export default {
  name: "app",
  components: {
    Landing
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
