<template>
  <div id="top-app">
    <index></index>
  </div>
</template>

<script>
import Index from "./views/Index.vue";

export default {
  name: "App",
  components: {
    Index
  }
};
</script>

<style>
body,
html {
  margin: 0;
  display: flex;
  height: 100%;
  width: 100%;
}

.index {
  height: 100%;
  width: 100%;
}

#top-app {
  width: 100%;
  height: 100%;
  right: 0;
}
</style>
