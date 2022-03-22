<template>
  <footer>
    <div class="contact">
      <div class="container py-5 contact-border">
        <div class="row">
          <div class="col-lg-3 contact-item">
            <img src="/images/white-logo.png" alt="" class="img-fluid w-100" />
            <div class="contact1 mt-4 mb-3">
              <a href="#">
                16501 Collins Ave, Sunny Isles Beach, FL 33160, United States</a
              >
            </div>
            <div class="contact1 my-3">
              <a href="#"> hexashop@company.com</a>
            </div>
            <div class="contact1 my-3">
              <a href="#"> 010-020-0340</a>
            </div>
          </div>
          <div class="col-lg-3 contact-item">
            <h4 class="my-3">Shopping & Categories</h4>
            <p><a href="#men">Men’s Shopping</a></p>
            <p><a href="#women">Women’s Shopping</a></p>
            <p><a href="#kid">Kid’s Shopping</a></p>
          </div>
          <div class="col-lg-3 contact-item">
            <h4 class="my-3">Usefull Link</h4>
            <p><a href="#">Home Page</a></p>
            <p><a href="#about-us">About Us</a></p>
            <p><a href="#">Help</a></p>
            <p><a href="#">Contact Us</a></p>
          </div>
          <div class="col-lg-3 contact-item">
            <h4 class="my-3">Help & Information</h4>
            <p><a href="#">Help</a></p>
            <p><a href="#">FAQ's</a></p>
            <p><a href="#">Shipping</a></p>
            <p><a href="#">Track ID</a></p>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="text-center text-white py-5">
          <p>Copyright © 2022 HexaShop Co., Ltd. All Rights Reserved.</p>
          <p>Design: <a href="#" class="text-info">TemplateMo</a></p>
          <br />
          <div class="list-icon">
            <a href="#">
              <b-icon-facebook class="icon-item"></b-icon-facebook>
            </a>
            <a href="#"><b-icon-twitter class="icon-item"></b-icon-twitter></a>
            <a href="#">
              <b-icon-linkedin class="icon-item"></b-icon-linkedin>
            </a>
            <a href="#">
              <b-icon-instagram class="icon-item"></b-icon-instagram>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.contact {
  background-color: #212529;
}
h4 {
  color: #cbcbcb;
}
a {
  text-decoration: none;
  color: #cbcbcb;
}
a:hover {
  color: #eee;
  text-decoration: none;
}
.contact-item {
  padding-left: 40px !important;
}
.contact-border {
  border-bottom: 1px #eee solid;
}
.icon-item {
  font-size: 2rem;
  margin-right: 2rem;
}
</style>
