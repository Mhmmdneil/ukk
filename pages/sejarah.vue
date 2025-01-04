<template>
  <div class="container">
      <div class="row">
          <div class="col">
              <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
                  <div class="carousel-indicators">
                      <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                          aria-current="true" aria-label="Slide 1"></button>
                      <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                          aria-label="Slide 2"></button>
                  </div>
                  <div class="carousel-inner">
                      <div class="carousel-item active" data-bs-interval="10000">
                          <img src="~/assets/img/gerbang.png" class="foto d-block w-100" alt="..." height="500">
                          <div class="carousel-caption d-none d-md-block">
                          </div>
                      </div>
                      <div class="carousel-item">
                          <img src="~/assets/img/tiga.png" class="foto d-block w-100" alt="..." height="500">
                          <div class="carousel-caption d-none d-md-block">
                          </div>
                      </div>
                  </div>
                  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
                      data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
                      data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                  </button>
              </div>
          </div>
          
      </div>
  </div>

  <.
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.container {
  max-width: 100%;
}

.judul {
  margin-left: 10%;
}

h4,
h5,
p {
  font-family: "Poppins", serif;
  margin-right: auto;
}

.card {
  width: 70%;
  margin: auto;
}

.foto {
  opacity: 0.5;
}

.foto:hover {
  opacity: 1.0;
}
</style>