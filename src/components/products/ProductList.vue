<template>
  <div class="product-list py-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h3>Our Latest Products</h3>
          <p><em class="text-muted">Check out all of our products.</em></p>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 mt-5" v-for="men in mens" :key="men.url">
          <div class="product">
            <div class="product-img position-relative">
              <img :src="men.url" alt="m1" class="img-fluid w-100" />
              <div class="list-icon position-absolute">
                <div class="icon-hover">
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-eye-fill class="icon"></b-icon-eye-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-star-fill class="icon"></b-icon-star-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-cart-fill class="icon"></b-icon-cart-fill>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-detail">
              <div class="title d-flex justify-content-between">
                <h3 class="py-3 mb-0">{{ men.title }}</h3>
                <div class="icon">
                  <div class="py-3">
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                  </div>
                </div>
              </div>
              <span class="text-secondary price">{{ men.price }}</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-5" v-for="women in womens" :key="women.url">
          <div class="product">
            <div class="product-img position-relative">
              <img :src="women.url" alt="m1" class="img-fluid w-100" />
              <div class="list-icon position-absolute">
                <div class="icon-hover">
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-eye-fill class="icon"></b-icon-eye-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-star-fill class="icon"></b-icon-star-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-cart-fill class="icon"></b-icon-cart-fill>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-detail">
              <div class="title d-flex justify-content-between">
                <h3 class="py-3 mb-0">{{ women.title }}</h3>
                <div class="icon">
                  <div class="py-3">
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                  </div>
                </div>
              </div>
              <span class="text-secondary price">{{ women.price }}</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-5" v-for="kid in kids" :key="kid.url">
          <div class="product">
            <div class="product-img position-relative">
              <img :src="kid.url" alt="m1" class="img-fluid w-100" />
              <div class="list-icon position-absolute">
                <div class="icon-hover">
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-eye-fill class="icon"></b-icon-eye-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-star-fill class="icon"></b-icon-star-fill>
                    </a>
                  </div>
                  <div class="p-3 mx-2 bg-white icon-item">
                    <a href="#sigle-product">
                      <b-icon-cart-fill class="icon"></b-icon-cart-fill>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="product-detail">
              <div class="title d-flex justify-content-between">
                <h3 class="py-3 mb-0">{{ kid.title }}</h3>
                <div class="icon">
                  <div class="py-3">
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                    <b-icon-star-fill class="icon-star mx-1"></b-icon-star-fill>
                  </div>
                </div>
              </div>
              <span class="text-secondary price">{{ kid.price }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mens: [
        {
          url: "/images/men-01.jpg",
          title: "Classic Spring",
          price: "$120.00",
        },
        {
          url: "/images/men-02.jpg",
          title: "Air Force 1 X",
          price: "$90.00",
        },
        {
          url: "/images/men-03.jpg",
          title: "Nana's Clother",
          price: "$150.00",
        },
      ],
      womens: [
        {
          url: "/images/women-01.jpg",
          title: "New Green Jacket",
          price: "$120.00",
        },
        {
          url: "/images/women-02.jpg",
          title: "Classic Dress",
          price: "$90.00",
        },
        {
          url: "/images/women-03.jpg",
          title: "Spring Collection",
          price: "$150.00",
        },
      ],
      kids: [
        {
          url: "/images/kid-01.jpg",
          title: "School Collection",
          price: "$120.00",
        },
        {
          url: "/images/kid-02.jpg",
          title: "Summer Cap",
          price: "$90.00",
        },
        {
          url: "/images/kid-03.jpg",
          title: "Classic Kid",
          price: "$150.00",
        },
      ],
    };
  },
};
</script>

<style scoped>
.icon-star {
  font-size: 12px !important;
}
.list-icon {
  top: 66%;
  left: 70px;
  opacity: 0;
}
.product-img:hover .list-icon {
  opacity: 1.2;
  cursor: pointer;
  transition: all 0.5s;
}
.icon-item {
  border-radius: 10px;
}
.icon {
  color: #212529;
}
</style>
