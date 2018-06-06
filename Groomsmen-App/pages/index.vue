<template>
  <section class="container">
    <nav-bar />
    <div>
      <app-logo/>
      <h1 class="title">
        groomsmen-app
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
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
  grid-template-columns: 1fr 5fr;
}
</style>
