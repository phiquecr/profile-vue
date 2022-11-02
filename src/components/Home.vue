<template>
  <div>
    <HeaderVue />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderVue from "./Header/Header.vue";

export default defineComponent({
  name: "AppVue",
  components: {
    HeaderVue,
  },
});
</script>
