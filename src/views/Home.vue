<template>
  <div id="home">
    <my-banner />
    <men-item />
    <women-item />
    <kid-item />
    <product />
    <social-media />
    <form-address />
  </div>
</template>

<script>
import MyBanner from "../components/home/MyBanner.vue";
import MenItem from "../components/home/MenItem.vue";
import WomenItem from "../components/home/WomenItem.vue";
import KidItem from "../components/home/KidItem.vue";
import Product from "../components/home/Product.vue";
import SocialMedia from "../components/home/SocialMedia.vue";
import FormAddress from "../components/home/FormAddress.vue";

export default {
  components: {
    MenItem,
    WomenItem,
    MyBanner,
    KidItem,
    Product,
    SocialMedia,
    FormAddress,
  },
};
</script>

<style></style>
