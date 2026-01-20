
<template>
  <div class="container py-5" id="action-carousel">
    <div class="row align-items-center">
      <div class="col-12 col-md-8">
        <div id="carouselExampleFade" class="carousel slide carousel-fade custom-carousel shadow-lg">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../../public/images/carousel1.png" class="d-block w-100" alt="Rider Action 1">
            </div>
            <div class="carousel-item">
              <img src="../../public/images/carousel2.png" class="d-block w-100" alt="Rider Action 2">
            </div>
            <div class="carousel-item">
              <img src="../../public/images/carousel3.png" class="d-block w-100" alt="Rider Action 3">
            </div>
          </div>
          
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
            <span class="carousel-control-prev-icon custom-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
            <span class="carousel-control-next-icon custom-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>

      <div class="col-12 col-md-4 mt-4 mt-md-0">
        <div class="info-card p-4">
          <h2 class="text-primary-blue fw-bold">Unleash the <span class="text-accent">Power</span></h2>
          <p class="text-muted">Explore the latest transformations and tech updates from the Rider universe.</p>
        </div>
      </div>
    </div>
  </div>
</template>