<template>
  <div id="app">
    <titleHeader msg="Welcome to Your Vue.js App" />
    <heroPage /> 

  </div>
</template>
<script>
import HeroPage from "./components/heroPage.vue";
import titleHeader from "./components/titleHeader.vue";
export default {
  name: "App",
  components: {
    titleHeader,
    HeroPage,
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
