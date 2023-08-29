<template>
    <div id="carouselExampleCaptions" class="carousel slide carousel-fade" data-bs-ride="true">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.postimg.cc/cCNVSTcn/peakpx-15.jpg" class="d-block w-100" alt="">
      <div class="carousel-caption d-none d-md-block">
        <h5><span class="red">Casio G-Shock</span></h5>
        <p>Water proof and shock resistant perfect for formal wear</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/zDtMznF6/peakpx-17.jpg" class="d-block w-100" alt="">
      <div class="carousel-caption d-none d-md-block">
        <h5><span class="red">Fossil</span></h5>
        <p>Aesthetic leather and perfect for formal wear</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/ZR2yK77V/peakpx-18.jpg" class="d-block w-100" alt="">
      <div class="carousel-caption d-none d-md-block">
        <h5><span class="red">Seiko</span></h5>
        <p>A brand Of luxury perfect for formal and business wear</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</template>
<script>

</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cinzel&display=swap');

.carousel.slide.fade {
    height: 35rem !important;
}

.carousel-item {
    height: 35rem !important;
}

.d-block.w-100 {
    height: 35rem !important;
}

.red {
    color: goldenrod;
    font-size: 2rem;
}

h5, p {
    font-family: 'Cinzel', serif;

}
</style>