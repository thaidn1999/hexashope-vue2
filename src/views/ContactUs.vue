<template>
  <div>
    <contact-banner />
    <contact-form />
    <form-address />
  </div>
</template>

<script>
import ContactBanner from "../components/contact/ContactBanner.vue";
import ContactForm from "../components/contact/ContactForm.vue";
import FormAddress from "../components/home/FormAddress.vue";
export default {
  components: { ContactBanner, ContactForm, FormAddress },
};
</script>

<style></style>
