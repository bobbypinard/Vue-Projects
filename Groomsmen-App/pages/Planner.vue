<template>
  <div class="Planner">
    <h1>Planner</h1>
    <todo />
  </div>
</template>

<script>
import Todo from '~/components/Todo.vue'

export default {
  components: {
    Todo
  }
}
</script>

<style>
h1 {
  text-align: center;
  font-family: 'Great Vibes';
  font-size: 4em;
  margin-bottom: 2em;
  border-bottom: 2px solid #ccac00;
}
.Planner {
}
</style>
