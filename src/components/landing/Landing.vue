<template>
  <section class="landing">
    <h1>{{ msg }}</h1>
    <Map />
  </section>
</template>

<script>
import Map from "./borough-map/Map";

export default {
  name: "Landing",
  components: {
    Map
  },
  props: {
    msg: String
  }
};
</script>
