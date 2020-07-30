<template>
  <div class="projects">
    <div class="projects_title">
      <h2 class="projects_title--text">Projetos</h2>
    </div>
    <div class="projects_content">
      <CardProjects
        v-for="card in cards"
        :key="card.title"
        :title="card.title"
        :body="card.body"
        :url="card.url"
      ></CardProjects>
    </div>
  </div>
</template>

<script>
import CardProjects from "../components/Card-Projects.vue";

export default {
  name: "Projects",
  components: {
    CardProjects,
  },

  data: function () {
    return {
      cards: [
        {
          title: "DogTour",
          body:
            "O DogTour é uma plataforma cujo objetivo é facilitar o agendamento de passeios com cães.",
          url: "https://github.com/RafaelBadaro/dogtour",
        },
        {
          title: "Disfluência",
          body:
            "Uma plataforma online para auxiliar os profissionais na área da linguagem e comunicação.",
          url: "https://github.com/LaercioNazareno/Disfluencia",
        },
        {
          title: "Sagrado",
          body:
            "Um software em windows forms para auxiliar na gestão de um restaurante.",
          url: "https://github.com/saldanhacl/sagrado-solucao",
        },
        {
          title: "Fisioterapia",
          body:
            "Um site com um jogo de cunho informativo sobre Respiração oral. Este projeto foi realizado como um projeto de extensão em conjunto com a Fisioterapia da PUC Minas.",
          url: " https://github.com/gmfonseca/tis4",
        },
        {
          title: "Guardian",
          body:
            "Um software para procura de estacionamentos com os melhores preços na sua região.",
          url: "https://github.com/JonathasSL/guardian-api",
        },
      ],
    };
  },
};
</script>

<style scoped>
.projects {
  background-color: #f4e9c1;
}

.projects_content {
  display: flex;
}

@media (max-width: 500px) {
  .projects_content {
    flex-direction: column;
    align-items: center;
  }
}
.projects_title {
  text-align: left;
  padding-left: 20px;
}
.projects_title--text {
  margin: 0;
  padding-top: 15px;
}
</style>

 