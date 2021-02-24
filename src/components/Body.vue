<template>
  <div class="body">
    <AboutMe></AboutMe>
    <Projects></Projects>
  </div>
</template>

<script>
import Projects from "../components/Projects.vue";
import AboutMe from "../components/AboutMe.vue";

export default {
  name: "Body",
  components: {
    Projects,
    AboutMe,
  },
};
</script>

<style scoped>
.body {
  display: grid;
}
</style>
