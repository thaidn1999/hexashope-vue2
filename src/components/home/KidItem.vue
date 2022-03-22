<template>
  <div class="kid-item">
    <div id="kid">
      <div class="container my-5">
        <div class="row">
          <div class="col-lg-6">
            <div class="title">
              <h3>Kid's Latest</h3>
              <p class="mb-0">
                <em class="text-secondary"
                  >Details to details is what makes Hexashop different from the
                  other themes.</em
                >
              </p>
            </div>
          </div>
        </div>
        <vueper-slides
          class="no-shadow my-5"
          slide-multiple
          infinite
          :visible-slides="3"
          :gap="3"
          :slide-ratio="1 / 4"
          :dragging-distance="70"
          :breakpoints="breakpoints"
        >
          <vueper-slide
            v-for="(slide, index) in slides"
            :key="index"
            style="padding-bottom: 45%"
          >
            <template #content>
              <div>
                <div class="position-relative">
                  <img :src="slide.url" alt="" class="img-fluid" />
                  <div class="img-hover position-absolute">
                    <div class="icon-hover">
                      <div class="p-3 mx-2 bg-white icon-item">
                        <a href="#sigle-product">
                          <b-icon-eye-fill class="icon"></b-icon-eye-fill
                        ></a>
                      </div>
                      <div class="p-3 mx-2 bg-white icon-item">
                        <a href="#sigle-product"
                          ><b-icon-star-fill class="icon"></b-icon-star-fill
                        ></a>
                      </div>
                      <div class="p-3 mx-2 bg-white icon-item">
                        <a href="#sigle-product"
                          ><b-icon-cart-fill class="icon"></b-icon-cart-fill
                        ></a>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="title-icon d-flex justify-content-between">
                  <h4 class="py-3 mb-0">
                    {{ slide.title }}
                  </h4>
                  <div class="list-icon py-3">
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                  </div>
                </div>
                <span class="text-secondary price">{{ slide.price }}</span>
              </div>
            </template>
          </vueper-slide>
        </vueper-slides>
      </div>
    </div>
  </div>
</template>

<script>
import { VueperSlides, VueperSlide } from "vueperslides";
import "vueperslides/dist/vueperslides.css";
export default {
  components: { VueperSlides, VueperSlide },
  data() {
    return {
      slides: [
        {
          url: "/images/kid-01.jpg",
          title: "Classic Spring",
          price: "$120.00",
        },
        {
          url: "/images/kid-02.jpg",
          title: "Air Force 1X",
          price: "$90.00",
        },
        {
          url: "/images/kid-03.jpg",
          title: "Love Nana's",
          price: "$150.00",
        },
        {
          url: "/images/kid-02.jpg",
          title: "Classic Spring",
          price: "$120.00",
        },
        {
          url: "/images/kid-01.jpg",
          title: "Air Force 1X",
          price: "$90.00",
        },
        {
          url: "/images/kid-03.jpg",
          title: "Love Nana's",
          price: "$150.00",
        },
        {
          url: "/images/kid-01.jpg",
          title: "Classic Spring",
          price: "$120.00",
        },
        {
          url: "/images/kid-02.jpg",
          title: "Air Force 1X",
          price: "$90.00",
        },
        {
          url: "/images/kid-01.jpg",
          title: "Love Nana's",
          price: "$150.00",
        },
        {
          url: "/images/kid-03.jpg",
          title: "Classic Spring",
          price: "$120.00",
        },
        {
          url: "/images/kid-01.jpg",
          title: "Air Force 1X",
          price: "$90.00",
        },
        {
          url: "/images/kid-02.jpg",
          title: "Love Nana's",
          price: "$150.00",
        },
      ],
      breakpoints: {
        1200: {
          slideRatio: 1 / 5,
          visibleSlides: 3,
        },
        992: {
          slideRatio: 1 / 3,
          visibleSlides: 2,
        },
        576: {
          slideRatio: 1 / 2,
          visibleSlides: 2,
          gap: 0,
          arrows: false,
          bulletsOutside: true,
        },
        // The order you list breakpoints does not matter, Vueper Slides will sort them for you.
        1100: {
          slideRatio: 1 / 4,
          visibleSlides: 3,
        },
      },
    };
  },
};
</script>

<style></style>
