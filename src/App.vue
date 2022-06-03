<template>
  <div id="app">
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./components/BaseCalc.vue";

export default {
  name: "app",
  components: {
    Calculator,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap");

#app {
  font-family: "Roboto";
  max-width: 600px;
  margin: 0 auto;
  padding: 2rem;
  font-weight: normal;
}
</style>
