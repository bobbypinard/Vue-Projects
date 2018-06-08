<template>
  <section class="container">
    <nav-bar />
    <h1 class="title">
      Best-Man-App
    </h1>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import NavBar from '~/components/NavBar.vue'

export default {
  components: {
    AppLogo,
    NavBar
  }
}
</script>

<style>
body {
  background-image: url("/assets/background.jpg");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
}

.container {
  display: grid;
  grid-template-columns: 2fr 5fr;
  height: 100%;
}
</style>
