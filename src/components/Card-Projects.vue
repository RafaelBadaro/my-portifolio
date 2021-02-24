<template>
  <div class="project_card">
    <div class="card_title">{{ title }}</div>
    <!-- <div class="card_body" :data-hover="body">Passe o mouse aqui!</div> -->
    <div class="card_body">{{ body }}</div>
    <a class="waves-effect waves-light btn repo_url" :href="url">Repositório</a>
  </div>
</template>

<script>
import "materialize-css/dist/css/materialize.css";
export default {
  name: "Card-Projects",
  props: {
    title: String,
    body: String,
    url: String,
  },
};
</script>

<style scoped>
.project_card {
  width: 200px;
  background-color: #fa824c;
  text-align: left;
  display: grid;
  grid-template-rows: auto 1fr auto;
  margin: 20px;
}
.card_title {
  padding-left: 10px;
  padding-top: 10px;
}
.card_body {
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 7px;
}
/* .card_body:hover {
  font-size: 0;
  transition: 0.5s ease;
}
.card_body:hover::after {
  content: attr(data-hover);
  font-size: 17px;
} */

.repo_url {
  margin: 10px;
}
</style>
