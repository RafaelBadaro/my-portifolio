<template>
  <div class="body">
    <AboutMe></AboutMe>
    <h1>Linguagens e tecnologias</h1>
    <h1>Projetos</h1>
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
    AboutMe
  }
};
</script>

<style scoped>
.body{
}
</style>
