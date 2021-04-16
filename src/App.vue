<template>
  <div>
    <header-page></header-page>
    <body-page></body-page>
    <footer-page></footer-page>
  </div>
</template>

<script>
import headerPage from "../src/components/headerPage.vue";
import bodyPage from "../src/components/bodyPage.vue";
import footerPage from "../src/components/footerPage.vue";

export default {
  name: "App",
  components: {
    headerPage,
    bodyPage,
    footerPage,
  },
};
</script>

<style>
</style>
