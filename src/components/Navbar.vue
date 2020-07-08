<template>
  <div>
    <nav class="navbar navbar-expand-sm navbar-light" id="navbar">
      <a class="navbar-brand" href="#">
        <img src="../assets/logo.png" alt />
      </a>
      <button
        class="navbar-toggler d-lg-none"
        type="button"
        data-toggle="collapse"
        data-target="#collapsibleNavId"
        aria-controls="collapsibleNavId"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapsibleNavId">
        <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
          <li class="nav-item active">
            <a class="nav-link" href="#">
              Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">News</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Resources</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
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

@media only screen and (max-width: 768px) {
  .navbar {
  padding: 1.5rem 2rem !important;
}
}
</style>
