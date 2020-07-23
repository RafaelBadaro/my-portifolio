<template>
  <div class="body">
    <AboutMe></AboutMe>
    <Projects></Projects>
    <a href="../assets/curriculo.pdf" download="curriculo_rafael_badaro.pdf" target="_blank">Baixar curriculo</a>
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
