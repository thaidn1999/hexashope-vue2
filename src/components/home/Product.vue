<template>
  <div id="explore">
    <div class="container mt-5">
      <div class="row">
        <div class="col-lg-6">
          <div class="intro">
            <h3>Explore Our Products</h3>
            <br />
            <p class="text-secondary">
              You are allowed to use this HexaShop HTML CSS template. You can
              feel free to modify or edit this layout. You can convert this
              template as any kind of ecommerce CMS theme as you wish.
            </p>
            <br />
            <div class="quote d-flex mb-4">
              <b-icon-chat-left-quote-fill class="icon-quote mr-3">
              </b-icon-chat-left-quote-fill>
              <span>
                <em>
                  You are not allowed to redistribute this template ZIP file on
                  any other website.
                </em>
              </span>
            </div>
            <p class="text-secondary">
              There are 5 pages included in this HexaShop Template and we are
              providing it to you for absolutely free of charge at our
              TemplateMo website. There are web development costs for us.
            </p>
            <br />
            <p class="secondary">
              If this template is beneficial for your website or business,
              please kindly
              <a href="#" class="support"><span>support us</span></a> a little
              via PayPal. Please also tell your friends about our great website.
              Thank you.
            </p>
            <br />
            <button class="btn discover">Discover More</button>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="row">
            <div class="col-lg-6">
              <div class="leather">
                <h4 class="leather-title">Leather Bags</h4>
                <p class="text-secondary"><em>Latest Collection</em></p>
              </div>
            </div>
            <div class="col-lg-6">
              <img
                src="/images/explore-image-01.jpg"
                alt="ex1"
                class="img-fluid w-100"
              />
            </div>
            <div class="col-lg-6">
              <img
                src="/images/explore-image-02.jpg"
                alt="ex1"
                class="img-fluid w-100"
              />
            </div>
            <div class="col-lg-6">
              <div class="leather">
                <h4 class="leather-title">Different Types</h4>
                <p class="text-secondary"><em>Over 304 Products</em></p>
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
#explore {
  border-bottom: 3px dotted #eee;
}
.col-lg-6 {
  margin-bottom: 30px;
}
h3 {
  font-size: 1.8rem;
  font-weight: 700;
}
.icon-quote {
  color: #333 !important;
  font-size: 3rem;
}

.support:hover {
  text-decoration: none !important;
}
.discover {
  border: 1px solid #333 !important;
  padding: 10px 20px;
}
.discover:hover {
  background-color: #333;
  color: #fff !important;
}
.discover:focus {
  box-shadow: none !important;
}
.leather {
  background-color: #f8f8f8;
  text-align: center;
  width: 100%;
  min-height: 255px;
}
.leather-title {
  padding-top: 100px;
  font-size: 1.5rem !important;
}
</style>
