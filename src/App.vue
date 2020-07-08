<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from "./components/Home.vue";
import "./assets/fonts.css";

export default {
  name: "App",
  components: {
    Home
  }
};
</script>

<style>
@import "./assets/fonts.css";
@import "~bootstrap/dist/css/bootstrap.css";
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap");

#app {
  font-family: "Josefin Sans";
}

.color-darkBlue {
  color: #151d41;
}

.color-green {
  color: #27debf !important;
}

.bg-green {
  background: #27debf;
}
</style>
