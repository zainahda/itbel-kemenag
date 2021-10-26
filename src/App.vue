<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      <nav class="navbar navbar-expand-lg navbar-dark bg-success" id="main-nav">
        <div class="container">
          <a class="navbar-brand">ITBEL Kemenag RI</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse text-center h-300"
            id="navbarNavDropdown"
          >
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page"
                  ><span></span><router-link to="/">Home</router-link></a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link"
                  ><router-link to="/about">About</router-link></a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link"
                  ><router-link to="/izin">Perizinan</router-link></a
                >
              </li>
            </ul>
            <div class="date ms-3 text-light">{{dateBuilder ()}}</div>
          </div>
        </div>
      </nav>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  methods: {
    dateBuilder() {
      let d = new Date();
      let months = [
        "Januari",
        "Februari",
        "Maret",
        "April",
        "Mei",
        "Juni",
        "Juli",
        "Augustus",
        "September",
        "Oktober",
        "November",
        "Desember",
      ];
      let days = [
        "Minggu",
        "Senin",
        "Selasa",
        "Rabu",
        "Kamis",
        "Jum'at",
        "Sabtu",
      ];
      let day = days[d.getDay()];
      let date = d.getDate();
      let month = months[d.getMonth()];
      let year = d.getFullYear();
      return `${day}, ${date} ${month} ${year}`;
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  z-index: 1;
}

#nav a {
  font-weight: bold;
  color: #fff;
  text-decoration: none;
}

#nav a:hover {
  background: #fff;
  color: #3e7c17;
  transition: 1s;
}

#nav a.router-link-exact-active {
  color: #161e54;
}
</style>
