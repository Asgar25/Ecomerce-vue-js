<template>
  <div class="home">
    <Carousel />
    <FeaturedProduct />
    <DiscountBanner />
    <NewProduct />
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from "@/components/Carousel.vue";
import FeaturedProduct from "@/components/FeaturedProduct.vue";
import DiscountBanner from "@/components/DiscountBanner.vue";
import NewProduct from "@/components/NewProduct.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    Carousel,
    FeaturedProduct,
    DiscountBanner,
    NewProduct,
    Footer
  }
};
</script>
