<template>
  <div id="app">
    <Section></Section>
  </div>
</template>

<script>
import Section from "./components/Section.vue";

export default {
  name: "App",
  components: {
    Section,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Fira+Sans&display=swap");
* {
  box-sizing: border-box;
  margin: 0;
}
body {
  font-family: "Fira Sans";
}
</style>
