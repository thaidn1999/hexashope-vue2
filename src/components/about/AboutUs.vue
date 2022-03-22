<template>
  <div class="about-us">
    <div class="container my-5">
      <div class="row">
        <div class="col-lg-6 mt-3">
          <div class="about-left">
            <img
              src="/images/about-left-image.jpg"
              alt="about-left"
              class="img-fluid"
            />
          </div>
        </div>
        <div class="col-lg-6 mt-3">
          <div class="about-right">
            <h3>About Us & Our Skills</h3>
            <p class="text-muted my-4">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod kon tempor incididunt ut labore.
            </p>
            <div class="quote d-flex">
              <b-icon-chat-left-quote-fill class="icon-quote mr-3">
              </b-icon-chat-left-quote-fill>
              <span>
                <em class="text-dark">
                  You are not allowed to redistribute this template ZIP file on
                  any other website.
                </em>
              </span>
            </div>
            <p class="text-muted py-4 about-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod kon tempor incididunt ut labore et dolore magna aliqua ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip.
            </p>
            <div class="list-icon mt-3">
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
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.about-us {
  border-bottom: 3px dotted #eee;
}
.about-right {
  padding-left: 2rem;
}
.icon-quote {
  color: #333 !important;
  font-size: 3rem;
}
.about-text {
  border-bottom: 3px dotted #eee;
}
.item-icon {
  color: #333 !important;
  font-size: 2.5rem;
  margin-right: 2.2rem;
}
</style>
