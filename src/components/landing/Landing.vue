<template>
  <section class="landing">
    <h1 class="landing__title">{{ msg }}</h1>
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

<style scoped>
.landing {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background: url("../../assets/nyc-aerial.jpg");
  background-size: cover;
  width: 100vw;
  height: 100vh;
  color: #fff;
  position: relative;
  z-index: 2;
}

.landing:after {
  content: "";
  position: absolute;
  width: 100vw;
  height: 100vh;
  z-index: -1;
  background: rgba(0, 0, 0, 0.65);
}

.landing__title {
  font-size: 30px;
  font-weight: 600;
  margin-bottom: 30px;
}
</style>
