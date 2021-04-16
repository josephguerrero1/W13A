<template>
  <div>
    <h1>
      This is the body section, where we have 3 colors: blue, red, and green.
    </h1>
      <blue-color></blue-color>
      <red-color></red-color>
      <green-color></green-color>
  </div>
</template>

<script>
import blueColor from "../components/blueColor.vue";
import redColor from "../components/redColor.vue";
import greenColor from "../components/greenColor.vue";

export default {
  name: "body-page",
  components: {
    blueColor,
    redColor,
    greenColor,
  },
};
</script>

<style scoped>
</style>