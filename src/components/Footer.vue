<template>
  <div class="footer">
    <div class="socials">
      <span class="socials-header">Redes sociais:</span>
      <div class="socials-links">
        <a class="social" id="instagram" href="https://www.instagram.com/rafabadaro/">
          <img class="social-img" src="../assets/insta.png" />
        </a>
        <a class="social" id="linkedIn" href="https://www.linkedin.com/in/rafael-badaro/">
          <img class="social-img linkedin" src="../assets/linkedin.png" />
        </a>
        <a class="social" id="github" href="https://github.com/RafaelBadaro">
          <img class="social-img" src="../assets/github.png" />
        </a>
      </div>
      <a class="waves-effect waves-light btn" href="/curriculo.pdf" download>
        Baixar curriculo
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  background-color: #70a0af;
  text-align: start;
}
.socials {
  margin-left: 20px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.socials-header {
  font-size: 22px;
}
.social-img {
  width: 100px;
  height: 100px;
}
.linkedin {
  width: 80px;
  height: 80px;
  margin-bottom: 10px;
}
</style>
