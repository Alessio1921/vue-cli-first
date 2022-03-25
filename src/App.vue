<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <titleHeader msg="Welcome to Your Vue.js App" />
    <div class="text-primary">ciao</div>
  </div>
</template>
<script>
import titleHeader from "./components/titleHeader.vue";
export default {
  name: "App",
  components: {
    titleHeader,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
@import "~bootstrap/dist/css/bootstrap.css";
</style>
