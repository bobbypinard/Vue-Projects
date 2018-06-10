<template>
  <section class="container">
    <nav-bar class="nav" />
    <todo class="todo" />
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import NavBar from '~/components/NavBar.vue'
import Todo from '~/components/Todo.vue'

export default {
  components: {
    AppLogo,
    NavBar,
    Todo
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

.nav {
  background-color: aqua;
}

.todo {
  background-color: purple;
}
</style>
