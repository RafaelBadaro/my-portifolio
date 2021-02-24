<template>
  <div class="aboutme">
    <div class="infos">
      <div class="infos__container">
        <div class="infos__texts">
          <div class="infos__texts__intro">
            <p class="intro__text">
              Oi! Meu nome é Rafael mas todo mundo me chama de Badaró, tenho 21 anos e moro em Belo Horizonte, Brasil.
              Comecei a estudar Engenharia de Software em 2016 na PUC minas e atualmente
              trabalho com desenvolvimento de software mas tenho uma paixão por scrum e
              agilismo.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="picture">
      <img src="../assets/pp.jpg" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style scoped>
.aboutme {
  background-color: #444b6e;
  color: white;
  display: flex;
  padding: 40px;
}



.infos {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.infos__container {
  padding: 20px 40px;
}

.intro__text {
  font-size: 24px;
}

.infos__texts__additional {
  text-align: start;
}
.infos__texts_list {
  font-size: 22px;
}
.list_item {
  padding: 10px 0;
}

.picture {
  display: flex;
  justify-content: center;
  flex-direction: column;
}

img {
  border-radius: 50%;
  max-width: 100%;
}

@media (max-width: 500px) {
  .aboutme {
    display: block;
  }
  .infos__container{
    padding: 0;
  }
}
</style>
