<template>
  <div id="app">
    <my-header />
    <router-view />
    <my-footer />
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader.vue";
import MyFooter from "./components/MyFooter.vue";
export default {
  components: {
    MyFooter,
    MyHeader,
  },
};
</script>
<style>
#app {
  font-family: "Poppins", sans-serif;
}
</style>
