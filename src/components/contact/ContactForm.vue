<template>
  <div class="contact-form py-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="left">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3723.8946155292438!2d105.83247801467799!3d21.0369022928767!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3135aba15ec15d17%3A0x620e85c2cfe14d4c!2zTMSDbmcgQ2jhu6cgdOG7i2NoIEjhu5MgQ2jDrSBNaW5o!5e0!3m2!1svi!2s!4v1647682615018!5m2!1svi!2s"
              width="500"
              height="450"
              style="border: 0"
              allowfullscreen=""
              loading="lazy"
            ></iframe>
          </div>
        </div>
        <div class="col-lg-6 py-5">
          <div class="right">
            <h3>Say Hello. Don't Be Shy!</h3>
            <p>
              <em class="text-muted">
                Details to details is what makes Hexashop different from the
                other themes.
              </em>
            </p>
            <div class="row">
              <div class="col-lg-6">
                <input
                  type="text"
                  placeholder="Your Name"
                  class="px-3 py-2 mb-3 w-100"
                />
              </div>
              <div class="col-lg-6">
                <input
                  type="email"
                  placeholder="Your Email"
                  class="px-3 py-2 mb-3 w-100"
                />
              </div>
            </div>
            <div class="row mb-3">
              <div class="col-lg-12">
                <textarea
                  name="Your message"
                  cols="60"
                  rows="5"
                  placeholder="Your message"
                  class="px-3 py-2 w-100"
                >
                </textarea>
              </div>
            </div>
            <div class="icon-button">
              <b-icon-cursor-fill></b-icon-cursor-fill>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.contact-form {
  border-bottom: 3px dotted #eee;
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
</style>
