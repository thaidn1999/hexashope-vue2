<template>
  <div class="about-product">
    <div class="container my-5">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h3>Our Amazing Team</h3>
          <p>
            <em class="text-muted">
              Details to details is what makes Hexashop different from the other
              themes.
            </em>
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 mt-4">
          <div class="product-item">
            <div class="product-img position-relative">
              <img
                src="/images/team-member-01.jpg"
                alt="sv1"
                class="img-fluid w-100"
              />
              <div class="list-icon position-absolute">
                <div class="icon-product position-absolute">
                  <a href="#">
                    <b-icon-facebook class="item-icon"></b-icon-facebook>
                  </a>
                  <a href="#">
                    <b-icon-twitter class="item-icon"></b-icon-twitter>
                  </a>
                  <a href="#">
                    <b-icon-linkedin class="item-icon"></b-icon-linkedin>
                  </a>
                  <a href="#">
                    <b-icon-instagram class="item-icon"></b-icon-instagram>
                  </a>
                </div>
              </div>
            </div>
            <div class="title text-center py-3">
              <h4>Ragnar Lodbrok</h4>
              <p><em class="text-muted">Product Caretaker</em></p>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-4">
          <div class="product-item">
            <div class="product-img position-relative">
              <img
                src="/images/team-member-02.jpg"
                alt="sv1"
                class="img-fluid w-100"
              />
              <div class="list-icon position-absolute">
                <div class="icon-product position-absolute">
                  <a href="#">
                    <b-icon-facebook class="item-icon"></b-icon-facebook>
                  </a>
                  <a href="#">
                    <b-icon-twitter class="item-icon"></b-icon-twitter>
                  </a>
                  <a href="#">
                    <b-icon-linkedin class="item-icon"></b-icon-linkedin>
                  </a>
                  <a href="#">
                    <b-icon-instagram class="item-icon"></b-icon-instagram>
                  </a>
                </div>
              </div>
            </div>
            <div class="title text-center py-3">
              <h4>Ragnar Lodbrok</h4>
              <p><em class="text-muted">Product Caretaker</em></p>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-4">
          <div class="product-item">
            <div class="product-img position-relative">
              <img
                src="/images/team-member-03.jpg"
                alt="sv1"
                class="img-fluid w-100"
              />
              <div class="list-icon position-absolute">
                <div class="icon-product position-absolute">
                  <a href="#">
                    <b-icon-facebook class="item-icon"></b-icon-facebook>
                  </a>
                  <a href="#">
                    <b-icon-twitter class="item-icon"></b-icon-twitter>
                  </a>
                  <a href="#">
                    <b-icon-linkedin class="item-icon"></b-icon-linkedin>
                  </a>
                  <a href="#">
                    <b-icon-instagram class="item-icon"></b-icon-instagram>
                  </a>
                </div>
              </div>
            </div>
            <div class="title text-center py-3">
              <h4>Ragnar Lodbrok</h4>
              <p><em class="text-muted">Product Caretaker</em></p>
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
.about-product {
  border-bottom: 3px dotted #eee;
}
.list-icon {
  background-color: rgba(0, 0, 0, 0.9);
  text-align: center;
  top: 0;
  width: 100%;
  bottom: 0;
  opacity: 0;
  transition: all 0.3s;
}
.product-img:hover .list-icon {
  opacity: 1;
}
.icon-product {
  top: 50%;
  left: 50px;
}
.item-icon {
  color: #fff !important;
  font-size: 2rem;
  margin-right: 2rem;
}
</style>
