<template>
  <div id="home" class="banner">
    <div class="container-fluid my-5">
      <div class="row">
        <div class="col-lg-6 mb-3">
          <div class="position-relative">
            <img
              src="/images/left-banner-image.jpg"
              alt="banner-left"
              class="img-fluid banner-img"
            />
          </div>
          <div class="position-absolute text-white banner-content-large">
            <h1 class="banner-title">We Are Hexashop</h1>
            <div class="my-3">
              <em>Awesome, clean & creative HTML5 Template</em>
            </div>
            <button class="btn text-white mt-3 banner-button">
              Purchase Now!
            </button>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="row">
            <div class="col-lg-6 mb-3">
              <div class="position-relative">
                <img
                  src="/images/baner-right-image-01.jpg"
                  alt="banner-right"
                  class="w-100 banner-img"
                />
              </div>
              <div
                class="text-center text-white position-absolute banner-content"
              >
                <h4>Women</h4>
                <div><em>Best Clother For Women</em></div>
              </div>
              <div class="banner-detail">
                <div class="detail">
                  <h4 class="mt-5">Women</h4>
                  <p>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  </p>
                  <button class="btn text-white mt-3 banner-button">
                    Discover More
                  </button>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mb-3">
              <div class="position-relative">
                <img
                  src="/images/baner-right-image-02.jpg"
                  alt="banner-right"
                  class="w-100 banner-img"
                />
              </div>
              <div
                class="text-center text-white position-absolute banner-content"
              >
                <h4>Men</h4>
                <div><em>Best Clother For Men</em></div>
              </div>
              <div class="banner-detail">
                <div class="detail">
                  <h4 class="mt-5">Men</h4>
                  <p>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  </p>
                  <button class="btn text-white mt-3 banner-button">
                    Discover More
                  </button>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mb-3">
              <div class="position-relative">
                <img
                  src="/images/baner-right-image-03.jpg"
                  alt="banner-right"
                  class="w-100 banner-img"
                />
              </div>
              <div
                class="text-center text-white position-absolute banner-content"
              >
                <h4>Kids</h4>
                <div><em>Best Clother For Kid</em></div>
              </div>
              <div class="banner-detail">
                <div class="detail">
                  <h4 class="mt-5">Kids</h4>
                  <p>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  </p>
                  <button class="btn text-white mt-3 banner-button">
                    Discover More
                  </button>
                </div>
              </div>
            </div>
            <div class="col-lg-6 mb-3">
              <div class="position-relative">
                <img
                  src="/images/baner-right-image-04.jpg"
                  alt="banner-right"
                  class="w-100 banner-img"
                />
              </div>
              <div
                class="text-center text-white position-absolute banner-content"
              >
                <h4>Accessories</h4>
                <div><em>Best Clother For Accessories</em></div>
              </div>
              <div class="banner-detail">
                <div class="detail">
                  <h4 class="mt-5">Accessories</h4>
                  <p>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  </p>
                  <button class="btn text-white mt-3 banner-button">
                    Discover More
                  </button>
                </div>
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

<style scoped>
.banner {
  margin-top: 160px;
  letter-spacing: 1px;
  border-bottom: 3px dotted #eee;
}
.banner-img {
  width: 943px;
}
.banner-content-large {
  top: 50%;
  left: 100px;
  transform: translateY(-50%);
}
.banner-content {
  top: 50%;
  left: 100px;
  transform: translateY(-50%);
}

.banner-detail {
  position: absolute;
  color: #fff;
  top: 15px;
  right: 30px;
  left: 30px;
  bottom: 15px;
  text-align: center;
  background-color: rgba(42, 42, 42, 0.97);
  opacity: 0;
  transition: all 0.7s;
}
.banner-detail:hover {
  opacity: 1.5;
  cursor: pointer;
}
.banner-title {
  font-size: 3.6rem;
  font-weight: 600;
}
.banner-button {
  border: 1px solid #fff !important;
  padding: 10px 20px;
}
.banner-button:hover {
  background-color: #fff;
  color: #333 !important;
}
.banner-button:focus {
  box-shadow: none !important;
}
/* responsive */
@media screen and (max-width: 991.99px) {
  .banner-content {
    top: 50%;
    left: 40%;
    transform: translateY(-50%);
  }
  .detail {
    margin-top: 200px;
  }
}
@media screen and (min-width: 992px) and (max-width: 1300px) {
  .banner-content {
    top: 50%;
    left: 10%;
    transform: translateY(-50%);
  }
  .detail {
    margin-top: 0;
  }
  .detail h4 {
    margin-top: 6px !important;
    font-size: 1rem !important;
  }
  .detail p {
    font-size: 14px;
  }
  .detail button {
    padding: 3px 6px !important;
    margin-top: 0 !important;
    font-size: 14px;
  }
}
</style>
