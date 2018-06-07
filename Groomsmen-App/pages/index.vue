<template>
  <section class="container">
    <nav-bar />
    <h1 class="title">
      Groomsmen-App
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
.container {
  display: grid;
  grid-template-columns: 2fr 5fr;
  height: 100%;
}
</style>
