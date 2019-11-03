<template>
  <div id="carousel  p-md-10 ">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            class="d-block w-100 img-fluid img-thumbnail rounded"
            src="../assets/carousel/banner-bg.jpg"
            alt="First slide"
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Every Thing is on Your Hand!</h5>
            <p>Simple Shopping,Save Time And Money!!!</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            class="d-block w-100 img-fluid img-thumbnail rounded"
            src="../assets/carousel/banner-b-2.jpg"
            alt="Second slide"
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Every Thing is on Your Hand!</h5>
            <p>Simple Shopping,Save Time And Money!!!</p>
          </div>
        </div>
        <div class="carousel-item">
          <img
            class="d-block w-100 img-fluid img-thumbnail rounded"
            src="../assets/carousel/banner-bg-3.jpg"
            alt="Third slide"
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Every Thing is on Your Hand!</h5>
            <p>Simple Shopping,Save Time And Money!!!</p>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>

    <div class="container mt-md-5">
      <div class="row">
        <div class="col-md-3 text-center shadow p-3 mb-5 bg-white rounded" v-for="i in 4" :key="i">
          <div class="card border-primary mb-3" style="max-width: 18rem;">
            <div class="card-header">
              <i class="fa fa-dollar-sign"></i>
            </div>
            <div class="card-body">
              <i class="fa fa-shopping-cart fa-2x"></i>
              <h6 class="card-title">MONEY BACK GURANTEE</h6>
              <h6 class="card-text">If you do not like our product</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
img {
  max-height: 600px;
}

h5,
p {
  color: black;
  font-size: 25px;
}
</style>