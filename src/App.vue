<template>
  <div id="app">
    <Alarm />
  </div>
</template>

<script>
import Alarm from "./components/Alarm";

export default {
  name: "App",
  components: {
    Alarm,
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
