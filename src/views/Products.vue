<template>
  <div>
    <product-banner />
    <product-list />
    <product-pagination />
  </div>
</template>

<script>
import ProductBanner from "../components/products/ProductBanner.vue";
import ProductList from "../components/products/ProductList.vue";
import ProductPagination from "../components/products/ProductPagination.vue";
export default {
  components: { ProductBanner, ProductList, ProductPagination },
};
</script>

<style></style>
