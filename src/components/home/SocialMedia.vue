<template>
  <div id="social">
    <div class="container my-5">
      <div class="row">
        <div class="col-lg-12">
          <div class="title">
            <h3>Social Media</h3>
            <p class="text-secondary">
              <em
                >Details to details is what makes Hexashop different from the
                other themes.</em
              >
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="container my-5">
      <div class="row">
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-01.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-02.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-03.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-04.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-05.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-2 p-0 mb-3">
          <div class="position-relative">
            <img
              src="/images/instagram-06.jpg"
              class="img-fluid w-100"
              alt="s1"
            />
            <div class="social-item position-absolute">
              <div class="item">
                <p class="mb-0"><a href="#">Fashion</a></p>
                <a href="#"><b-icon-camera-fill></b-icon-camera-fill></a>
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
#social {
  border-bottom: 3px dotted #eee;
}
a {
  text-decoration: none !important;
  color: #fff;
}
a:hover {
  color: #fff;
}
.position-relative:hover {
  cursor: pointer;
}

.social-item {
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  opacity: 0;
  background-color: rgba(0, 0, 0, 0.85);
}
.position-relative:hover .social-item {
  opacity: 1.2;
  transition: all 0.5s;
}
.item {
  padding-top: 130px;
  padding-left: 16px;
}
/* responsive */
@media screen and (min-width: 576px) and (max-width: 767.99px) {
  .item {
    padding-top: 80%;
    padding-left: 8%;
    font-size: 1.2rem;
  }
}
@media screen and (min-width: 768px) and (max-width: 991px) {
  .item {
    padding-top: 600px;
    padding-left: 60px;
    font-size: 1.4rem;
  }
}
@media screen and (min-width: 992px) and (max-width: 1199px) {
  .item {
    padding-top: 100px;
  }
}
</style>
