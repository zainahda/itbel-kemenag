<template>
  <div class="hero">
    <!-- jumbotron start here -->
    <div class="jumbotron jumbotron-fluid">
      <div class="container text-center">
        <img
          class="image-display mt-5 animate__animated animate__zoomIn"
          src="../assets/logo_depag.png"
          alt="logo-depag"
        />
        <h4 class="lead fw-bold mt-3 animate__animated animate__fadeInUp">
          BIRO KEPEGAWAIAN
        </h4>
        <h5 class="sub-lead animate__animated animate__fadeInUp">
          SEKRETARIAT JENDERAL KEMENTERIAN AGAMA REPUBLIK INDONESIA
        </h5>
      </div>
    </div>
    <!-- jumbotron end here -->
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
};
</script>

<style scoped>
.jumbotron {
  background: #1d976c;
  background: -webkit-linear-gradient(to right, #1d976c, #93f9b9);
  background: linear-gradient(to right, #1d976c, #93f9b9);
  width: 100%;
  height: 85vh;
}

.hero img {
  width: 350px;
}

.hero h4,
h5 {
  color: #fff;
  text-shadow: 2px 2px #000;
}

.hero h4 {
  font-size: 35px;
}

.hero h5 {
  font-size: 25px;
}

@media (min-width: 1200px) {
  .hero img {
    width: 450px;
  }

  .hero h4 {
    font-size: 50px;
  }

  .hero h5 {
    font-size: 30px;
  }
}
</style>