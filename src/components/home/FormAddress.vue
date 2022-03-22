<template>
  <div id="address">
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-8 pr-4">
          <div class="title-left">
            <h3>By Subscribing To Our Newsletter You Can Get 30% Off</h3>
            <p class="text-secondary">
              <em
                >Details to details is what makes Hexashop different from the
                other themes.</em
              >
            </p>
          </div>
          <div class="row my-5">
            <div class="col-lg-5">
              <input
                type="text"
                placeholder="Your Name"
                class="w-100 form-input"
              />
            </div>

            <div class="col-lg-5">
              <input
                type="text"
                placeholder="Your Email Address"
                class="w-100 form-input"
              />
            </div>
            <div class="col-lg-2">
              <div class="icon-button">
                <b-icon-cursor-fill></b-icon-cursor-fill>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="row">
            <div class="col-lg-6">
              <div class="title-right">
                <div>
                  <h5>Store Location:</h5>
                  <p class="text-secondary">
                    Sunny Isles Beach, FL 33160, United States
                  </p>
                </div>
                <br />
                <div>
                  <h5>Phone:</h5>
                  <p class="text-secondary">010-020-0340</p>
                </div>
                <br />
                <div>
                  <h5>Office Location:</h5>
                  <p class="text-secondary">North Miami Beach</p>
                </div>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="title-right">
                <div>
                  <h5>Work Hours:</h5>
                  <p class="text-secondary">07:30 AM - 9:30 PM Daily</p>
                </div>
                <br />
                <div>
                  <h5>Email:</h5>
                  <p class="text-secondary">info@company.com</p>
                </div>
                <br />
                <div>
                  <h5>Social Media:</h5>
                  <p class="text-secondary">
                    Facebook, Instagram, Behance, Linkedin
                  </p>
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
h5 {
  font-size: 16px !important;
  font-weight: 700;
}
.icon-button {
  border: 1px solid #333;
  text-align: center;
  font-size: 1.8rem;
  color: #fff;
  background-color: #333;
  cursor: pointer;
}
.icon-button:hover {
  color: #333;
  background-color: #fff;
}
.form-input {
  padding: 9px 18px;
  color: #333;
}
/* responsive */
@media screen and (max-width: 991px) {
  .form-input {
    margin-bottom: 1rem;
  }
}
</style>
