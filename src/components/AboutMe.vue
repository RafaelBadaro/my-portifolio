<template>
  <div class="aboutme">
    <div class="infos">
      <div class="infos__container">
        <h1 class="infos__title">Sobre mim</h1>
        <div class="infos__texts">
          <div class="infos__texts__intro">
            <p class="intro__text">
              Oi! Meu nome é Rafael mas todo mundo me chama de Badaró e tenho 21 anos.
              Sou um estudante de engenharia de software e atualmente
              trabalho com desenvolvimento de software mas tenho uma paixão por scrum e
              agilismo.
            </p>
          </div>
          <div class="infos__texts__additional">
            <ul>
              <li>
                Onde trabalho atualmente: dti digital
                <ul>
                  <li>Duração: 2 anos</li>
                </ul>
              </li>
              <li>
                Linguagens e Frameworks:
                <ul>
                  <li>C#</li>
                  <li>Java</li>
                  <li>Angular</li>
                  <li>Vue.js</li>
                  <li>Python</li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="picture">
      <img src="../assets/eu.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe"
};
</script>

<style scoped>
.aboutme {
  background-color: #444b6e;
  color: white;
  display: flex;
}

.infos__container {
  padding: 20px 40px;
}
.infos__texts {
  display: flex;
}
.infos__texts__intro {
  width: 55%;
}
.infos__title {
  justify-content: start;
  display: flex;
}

.intro__text {
  font-size: 17px;
}

img {
  border-radius: 50%;
}
</style>
