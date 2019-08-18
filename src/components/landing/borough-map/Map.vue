<template>
  <svg class="boroughs-map" viewBox="0 0 1999.709 1977.598">
    <Brooklyn />
    <Bronx />
    <Manhattan />
    <StatenIsland />
    <Queens />
  </svg>
</template>

<script>
import Brooklyn from "./Brooklyn";
import Bronx from "./Bronx";
import Manhattan from "./Manhattan";
import StatenIsland from "./StatenIsland";
import Queens from "./Queens";

export default {
  name: "Map",
  components: {
    Brooklyn,
    Bronx,
    Manhattan,
    StatenIsland,
    Queens
  }
};
</script>


<style scoped>
.boroughs-map {
  position: relative;
  height: 75vh;
  width: 75vw;
  z-index: 2;
}

.borough {
  cursor: pointer;
}
</style>

