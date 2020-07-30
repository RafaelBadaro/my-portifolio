<template>
  <div class="project_card">
    <div class="card_title">{{title}}</div>
    <div class="card_body">
      <p>{{body}}</p>
      <a :href="url">Repositório</a>
    </div>
  </div>
</template>

<script>
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
  height: 250px;
  background-color: #fa824c;
  text-align: left;
  display: grid;
  grid-template-rows: auto 1fr;
  margin: 20px;
}
.card_title {
  padding-left: 10px;
  padding-top: 10px;
}
.card_body {
  padding-left: 10px;
  padding-right: 10px;
}
</style>
