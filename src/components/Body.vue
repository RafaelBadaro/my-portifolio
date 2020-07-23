<template>
  <div class="body">
    <AboutMe></AboutMe>
    <Projects></Projects>
    <a href="/curriculo.pdf" download>Baixar curriculo</a>
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
</style>
