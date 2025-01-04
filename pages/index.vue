<template>
  <div class="card text-bg-dark">
    <img src="assets/pembuka.jpg" class="card-img" alt="...">
    <div class="card-img-overlay">
      <h1 class="card-title" ><img src="pembuka.png" alt="logo" width="150px" height="150px"><p></p>>informasi
        Mengenai Smkn 4 Tasikmalaya</h1>
        <p class="berita">berita</p>
        <p class="berita">daftar guru</p>
        <Nuxt-Link to="./bacaselengkapnya" class="nav-link activate" aria-current="page" style="color:aquamarine;">
          <button class="baca rounded-2"><h6 style="color: blue;">baca selengkapnya</h6></button>
        </Nuxt-Link>
    </div>
  </div>
</template>

<style scoped>
.card-title{
  padding-top: 12%;
  color:black;
  justify-content: center;
}
.berita{
  color: brown;
  margin: 0%;
}

.nav-items{
  text-align: center;
}

.nav-link{
  padding: 1%;
}
</style>