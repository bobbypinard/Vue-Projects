<template>
  <section class="container">
    <todo class="todo" />
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Todo from '~/components/Todo.vue'

export default {
  components: {
    AppLogo,
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
</style>
