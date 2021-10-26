<template>
  <div class="permission d-flex align-items-center animate__animated animate__fadeInRight">
    <div class="container">
      <div class="row row-cols-1 row-cols-lg-5 g-4">
        <div class="col">
          <div class="card h-100">
            <img
              src="../assets/pendaftaran.png"
              class="card-img-top"
              alt="daftar-belajar"
            />
            <div class="card-body text-center">
              <h5 class="card-title">Pendaftaran Izin Belajar</h5>
              </div>
              <div class="card-footer d-flex justify-content-center bg-transparent">
                <a
                  href="https://docs.google.com/forms/d/1uGPnsEJvs9tpC-tZZ5kRz-OeLcRapLHDh_JglgkrytQ/viewform?edit_requested=true"
                  class="btn btn-lg btn-success"
                  >Daftar Sekarang</a
                >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img
              src="../assets/izin-belajar.png"
              class="card-img-top"
              alt="daftar-belajar"
            />
            <div class="card-body text-center">
              <h5 class="card-title">
                Pendaftaran Perpanjangan Izin Belajar
              </h5>
              </div>
              <div class="card-footer d-flex justify-content-center bg-transparent">
              <a
                href="https://docs.google.com/forms/d/1CbeGkgWnLIR6nKjcAJXJkqKox2pQ5BSI4F5prNOj868/viewform?edit_requested=true"
                class="btn btn-lg btn-success"
                >Daftar Sekarang</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img
              src="../assets/tugas-belajar.png"
              class="card-img-top"
              alt="daftar-belajar"
            />
            <div class="card-body text-center">
              <h5 class="card-title">Pendaftaran Tugas Belajar</h5>
              </div>
              <div class="card-footer d-flex justify-content-center bg-transparent">
              <a
                href="https://docs.google.com/forms/d/1OWpP0wzxmO805BTztfAS_u7zoBpMA8X0YXltmcsnOPY/viewform?edit_requested=true"
                class="btn btn-lg btn-success"
                >Daftar Sekarang</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img
              src="../assets/perpanjangan-tugas-belajar.png"
              class="card-img-top"
              alt="daftar-belajar"
            />
            <div class="card-body text-center">
              <h5 class="card-title">
                Pendaftaran Perpanjangan Tugas Belajar
              </h5>
              </div>
              <div class="card-footer d-flex justify-content-center bg-transparent">
              <a
                href="https://docs.google.com/forms/d/1aTuuBpXCeprCN1KQ5qq2tVkJ_jrwxt4D6K3NbWhH3h4/viewform?edit_requested=true"
                class="btn btn-lg btn-success"
                >Daftar Sekarang</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img
              src="../assets/tugas-belajar-izin-belajar.png"
              class="card-img-top"
              alt="daftar-belajar"
            />
            <div class="card-body text-center">
              <h5 class="card-title">
                Pendaftaran Perpanjangan Tugas Belajar Menjadi Izin Belajar
              </h5>
              </div>
              <div class="card-footer d-flex justify-content-center bg-transparent">
              <a
                href="https://docs.google.com/forms/d/1lsMhW2FAJF9m303C7kEwDKD1VvcqY5ZlBuvbpCZP1s4/viewform?edit_requested=true"
                class="btn btn-lg btn-success"
                >Daftar Sekarang</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Permission",
};
</script>

<style scoped>
.permission {
  height: 80vh;
}
h5 {
  font-size: 18px;
}
.card:hover {
  scale: 1.1;
  border: 1px solid #198754 ;
}
.permission {
  margin: 1150px 0;
}
@media (min-width: 1200px) {

}
</style>