<template>
  <div class="detail py-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-8">
          <div class="left">
            <img
              src="/images/single-product-01.jpg"
              alt="sg1"
              class="img-fluid w-100 mb-4"
            />
            <img
              src="/images/single-product-02.jpg"
              alt="sg1"
              class="img-fluid w-100"
            />
          </div>
        </div>
        <div class="col-lg-4">
          <div class="right">
            <div class="top-detail pb-4">
              <div class="title d-flex justify-content-between">
                <h4 class="py-3 mb-0">New Green Jacket</h4>
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
              <span class="text-muted price">$75.00</span>
            </div>
            <div class="text-detail py-4">
              <p class="text-muted">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod kon tempor incididunt ut labore.
              </p>
              <div class="quote d-flex">
                <b-icon-chat-left-quote-fill class="icon-quote mr-3">
                </b-icon-chat-left-quote-fill>
                <span>
                  <em>
                    You are not allowed to redistribute this template ZIP file
                    on any other website.
                  </em>
                </span>
              </div>
            </div>
            <div
              class="amount-product d-flex justify-content-between py-4 text-detail"
            >
              <h4 class="text-muted">No. of Orders</h4>
              <div class="button-total">
                <button @click="decrease()">-</button>
                <button>{{ this.count }}</button>
                <button @click="increase()">+</button>
              </div>
            </div>
            <div class="total-product d-flex justify-content-between py-4">
              <h4 class="text-muted">Total: $210.00</h4>
              <a href="#"><button class="add-card">Add To Card</button></a>
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
      count: 1,
    };
  },

  methods: {
    decrease() {
      if (this.count <= 1) {
        return this.count;
      } else {
        return this.count--;
      }
    },
    increase() {
      return this.count++;
    },
  },
};
</script>

<style scoped>
button {
  background-color: #fff;
  padding: 5px 10px;
  border: 1px solid #ccc;
}
.icon-star {
  font-size: 12px !important;
}
.icon-item {
  border-radius: 10px;
}
.icon {
  color: #212529;
}
.top-detail {
  border-bottom: 1px solid #eee;
}
.text-detail {
  border-bottom: 1px solid #eee;
}
.icon-quote {
  color: #333 !important;
  font-size: 2rem;
}
.add-card {
  padding: 10px 16px;
}
.add-card:hover {
  color: #fff;
  background-color: #333;
}
</style>
