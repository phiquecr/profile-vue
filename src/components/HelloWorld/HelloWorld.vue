<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  data() {
    return {
      title: "HelloWorld",
      message: "This commit signals the start of the project.",
    };
  },
});
</script>

<style scoped>
.hello {
  display: flex;
  align-items: center;
  flex-direction: column;
  gap: 0.5rem;
  font-family: sans-serif;
}
.hello h1 {
  font-size: 2rem;
}
.hello p {
  font-size: 1rem;
}
</style>
