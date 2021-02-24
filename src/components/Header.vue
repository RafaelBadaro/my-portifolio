<template>
  <div class="header">
    <h4>Contato: rafaelaraujobadaro@gmail.com</h4>
    <div class="socials">
      <div class="socials-links">
        <a
          class="social"
          id="instagram"
          href="https://www.instagram.com/rafabadaro/"
        >
          <img class="social-img" src="../assets/insta.png" />
        </a>
        <a
          class="social"
          id="linkedIn"
          href="https://www.linkedin.com/in/rafael-badaro/"
        >
          <img class="social-img linkedin" src="../assets/linkedin.png" />
        </a>
        <a class="social" id="github" href="https://github.com/RafaelBadaro">
          <img class="social-img" src="../assets/github.png" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  background-color: #70a0af;
}
.socials {
  margin-left: 20px;
  display: flex;
  align-items: center;
  flex-direction: column;
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
