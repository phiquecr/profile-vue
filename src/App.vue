<template>
  <div class="app">
    <HomeVue />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HomeVue from "./components/Home.vue";

export default defineComponent({
  name: "AppVue",
  components: {
    HomeVue,
  },
});
</script>

<style scoped>
.app {
  width: 100%;
  height: 100vh;
}
</style>
