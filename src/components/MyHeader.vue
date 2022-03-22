<template>
  <div id="my-navbar">
    <div class="my-header">
      <div class="container">
        <b-navbar toggleable="lg">
          <b-navbar-brand href="#home">
            <img src="/images/logo.png" alt="logo" class="img-fluid" />
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <b-nav-item active>
                <router-link :to="{ name: 'Home' }"> Home </router-link>
              </b-nav-item>
              <b-nav-item href="#men">Men</b-nav-item>
              <b-nav-item href="#women">Women's</b-nav-item>
              <b-nav-item href="#kid">Kid's</b-nav-item>
              <b-nav-item-dropdown class="drop" text="Pages" right>
                <b-dropdown-item>
                  <router-link :to="{ name: 'About' }"> About Us </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'Products' }">
                    Products
                  </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'SingleProduct' }">
                    Single Product
                  </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'ContactUs' }">
                    Contact Us
                  </router-link>
                </b-dropdown-item>
              </b-nav-item-dropdown>
              <b-nav-item-dropdown text="Features" right>
                <b-dropdown-item>
                  <router-link :to="{ name: 'Feature1' }">
                    Feature1
                  </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'Feature2' }">
                    Feature2
                  </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'Feature3' }">
                    Feature3
                  </router-link>
                </b-dropdown-item>
                <b-dropdown-item>
                  <router-link :to="{ name: 'Feature4' }">
                    Feature4
                  </router-link>
                </b-dropdown-item>
              </b-nav-item-dropdown>
              <b-nav-item href="#explore">Explore</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  color: rgba(0, 0, 0, 0.7) !important;
  text-decoration: none !important;
}
a:hover {
  color: #000 !important;
  text-decoration: none !important;
}

.my-header {
  width: 100%;
  height: 80px;
  background-color: #fff;
  top: 0;
  position: fixed;
  z-index: 1000;
  border-bottom: 3px dotted #eee;
}
.top-header {
  position: relative;
  height: 100px;
  background-color: #fff;
}
.logo {
  line-height: 100px;
}
.nav-item {
  font-size: 16px;
  padding: 4px 16px !important;
  font-weight: 500;
}

.navbar-expand-lg .navbar-collapse {
  justify-content: flex-end;
}
@media screen and (max-width: 991.99px) {
  .my-header {
    height: auto;
  }
}
</style>
