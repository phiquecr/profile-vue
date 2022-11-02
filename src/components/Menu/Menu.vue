<template>
  <nav>
    <ul>
      <li>
        <a href="#">{{ links[0] }}</a>
      </li>
      <li>
        <a href="#">{{ links[1] }}</a>
      </li>
      <li>
        <a href="#">{{ links[2] }}</a>
      </li>
    </ul>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "MenuItem",
  data() {
    return {
      links: ["Home", "Portfolio", "Contact"],
    };
  },
});
</script>

<style scoped>
nav {
  display: flex;
  justify-content: flex-end;
  width: 100%;
  margin: 0 6rem;
}
ul {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 4rem;
}
li {
  list-style: none;
}
a {
  text-decoration: none;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: aliceblue;
}
a:hover {
  color: blueviolet;
  transition: 0.3s;
}
</style>
