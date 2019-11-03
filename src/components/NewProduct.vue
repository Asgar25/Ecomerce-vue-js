<template>
  <div id="newProduct" class="container mt-md-5 text-center shadow p-3 mb-5 bg-white rounded">
    <h1 class="text-center">NEW PRODUCT</h1>
    <h4 class="text-center">Brand New Products</h4>
    <div class="row">
      <div class="col-lg-12 p-md-5 mt-lg-5">
        <h4>COLLECTION OF 2019</h4>
        <h2>MEN’S SUMMER T-SHIRT</h2>
        <img src="../assets/newProduct/new-product1.png" alt />
        <h5>$120.70</h5>
        <button class="btn btn-success">ADD TO CART</button>
      </div>

      <div class="col-lg-12 text-center p-md-5 mt-md-3">
        <div class="row">
          <div class="col-sm-3 shadow p-3 mb-5 bg-white rounded" v-for="i in 4" :key="i">
            <img src="../assets/newProduct/n1.jpg" alt />
            <div class="row mt-md-3">
              <div class="col-md-4">
                <i class="fa fa-heart fa-2x"></i>
              </div>
              <div class="col-md-4">
                <i class="fa fa-eye fa-2x"></i>
              </div>
              <div class="col-md-4">
                <i class="fa fa-shopping-cart fa-2x"></i>
              </div>
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
</style>