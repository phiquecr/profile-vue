<template>
  <div class="app">
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld/HelloWorld.vue";

export default defineComponent({
  name: "AppVue",
  components: {
    HelloWorld,
  },
});
</script>

<style scoped>
.app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
}
</style>
