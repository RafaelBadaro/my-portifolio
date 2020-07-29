<template>
  <div class="projects">
    <div class="projects_title">
      <h2>Projetos</h2>
    </div>
    <div class="projects_content">
      <Card-Projects></Card-Projects>
    </div>
  </div>
</template>

<script>
import Card_Projects from "../components/Card-Projects.vue";

export default {
  name: "Projects",
    components: {
    Card_Projects
  },
};
</script>

<style scoped>
.projects_title {
  text-align: left;
  padding-left: 30px;
}

</style>
