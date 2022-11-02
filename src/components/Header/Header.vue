<template>
  <header>
    <MenuVue />
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import MenuVue from "../Menu/Menu.vue";

export default defineComponent({
  name: "HeaderItem",
  components: {
    MenuVue,
  },
});
</script>

<style scoped>
header {
  top: 0;
  display: flex;
  width: 100%;
  height: 4rem;
  background-color: rgb(9, 10, 31);
}
</style>
