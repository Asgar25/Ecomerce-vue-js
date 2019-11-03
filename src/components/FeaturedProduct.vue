<template>
  <div class="container mt-md-5">
    <h1 class="text-center">FEATURED PRODUCT</h1>
    <div class="row">
      <div class="col-md-4 shadow p-3 mb-5 bg-white rounded" v-for="i in 3" :key="i">
        <div class="thumbnail">
          <img
            src="../assets/featuredProduct/f-p-1.jpg"
            style="max-height:400px;"
            class="img-responsive"
          />
          <div class="caption">
            <div class="row">
              <div class="col-md-6 col-xs-6">
                <h3>Shoes</h3>
              </div>
              <div class="col-md-6 col-xs-6 price">
                <h3>
                  <label>$649.99</label>
                </h3>
              </div>
            </div>
            <div class="row">
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