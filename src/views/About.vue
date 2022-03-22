<template>
  <div id="about">
    <about-banner />
    <about-us />
    <about-product />
    <about-service />
    <form-address />
  </div>
</template>

<script>
import AboutBanner from "../components/about/AboutBanner.vue";
import AboutProduct from "../components/about/AboutProduct.vue";
import AboutService from "../components/about/AboutService.vue";
import AboutUs from "../components/about/AboutUs.vue";
import FormAddress from "../components/home/FormAddress.vue";
export default {
  components: { AboutBanner, AboutUs, AboutProduct, AboutService, FormAddress },
};
</script>

<style></style>
