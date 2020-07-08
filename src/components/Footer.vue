<template>
  <div>
    <footer class="container-fluid px-5 py-5">
      <div class="row d-flex flex-column flex-md-row flex-lg-row justify-content-md-between justify-content-lg-between">
        <div class="col-md-4">
          <img src="../assets/logo.png" alt />
          <p
            class="color-darkBlue mt-2"
          >Lorem ipsum dolor sit amet,Stet clita kasd gubergren, no sea takimata</p>
        </div>
        <div class="col-md-7 d-flex flex-column align-items-start align-items-md-end align-items-lg-end">
          <h5 class="color-darkBlue font-weight-bold">We are digital designer living in United States. Apart from eating burgers</h5>
          <div class="d-flex flex-column flex-md-row flex-lg-row mt-3">
              <div class="d-flex flex-column">
                  <h6 class="color-green">SEND MAIL</h6>
                  <h6 class="mt-0 color-darkBlue">
                      info@portfolio.com
                  </h6>
              </div>
              <div class="d-flex flex-column pl-md-4">
                  <h6 class="color-green">MAKE CALL</h6>
                  <h6 class="mt-0 color-darkBlue">
                      +123 456 7890
                  </h6>
              </div>
              <div class="d-flex flex-column pl-md-4">
                  <h6 class="color-green">GET IN TOUCH</h6>
                  <h6 class="mt-0 color-darkBlue">
                      123/A, Hamburger City New York, USA
                  </h6>
              </div>
          </div>
        </div>

      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {}
};
</script>

<style scoped>
.navbar {
  padding: 3rem 5rem !important;
  position: relative;
  z-index: 2;
}

.nav-item a {
  font-weight: bold !important;
  font-size: 0.9rem;
  padding: 0px !important;
  margin: 0rem 1.4rem;
  color: #5b5b5b !important;
  transition: 0.2s all ease;
  -moz-transition: 0.2s all ease;
  -webkit-transition: 0.2s all ease;
}

.nav-item a:hover {
  color: #000000 !important;
}

.nav-item.active a {
  color: #000000 !important;
}
</style>
