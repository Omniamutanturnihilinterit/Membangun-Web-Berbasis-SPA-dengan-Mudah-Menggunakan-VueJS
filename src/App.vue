<template>
  <div id="app">
    <h1>Kalkulator Sederhana Dengan Vuejs</h1>
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./components/Calculator";

export default {
  name: "App",
  components: {
    Calculator,
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
