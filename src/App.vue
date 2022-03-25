<template>
  <div id="app" class="bg-primary text-center">
    <titleHeader />
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

@import "~bootstrap/dist/css/bootstrap.css";
</style>
