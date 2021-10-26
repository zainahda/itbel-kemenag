<template>
  <div class="about">
    <div class="about-text text-start">
      <h1 class="fw-bold text-justify animate__animated animate__fadeInDown">
        <img
          class="about-image animate__animated animate__fadeInRight"
          src="../assets/about.svg"
          alt="about-pict"
        />
        Selamat datang di website ini <br />
        kepada Bapak/Ibu admin izin/tugas belajar wilayah <br />
        Provinsi Aceh, Jawa Tengah, Sulawesi Selatan dan unit Eselon I Pusat
      </h1>
      <p class="text-justify animate__animated animate__slideInUp">
        Semoga dengan adanya website ini dapat memudahkan kita dalam menginput
        data izin/tugas belajar, meminimalkan kesalahan dalam penulisan data
        serta mengurangi biaya ongkos kirim berkas. Berkas fisik yang ada di
        Bapak/Ibu dapat diarsipkan jika sewaktu-waktu diperlukan.
        <br />
        Terimakasih
        <br />
        <br />
        Hormat saya
        <br />
        <br />
        Rahmatullah, S.Ag.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.about h1 {
  font-size: 28px;
  padding: 100px 100px 0 100px;
}

.about p {
  font-size: 25px;
  padding: 0 100px;
}

img {
  float: clear;
}

.about-image {
  width: 350px;
  height: 350px;
  display: flex;
  justify-content: center;
  margin: 0;
}

@media (min-width: 1200px) {
  .about-image {
    width: 500px;
    height: 500px;
    margin: -60px 0 0 35px;
  }
  img {
    float: right;
  }
}
</style>>
