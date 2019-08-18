<template>
  <Landing msg="The Five Boroughs of NYC" />
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
:root {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
