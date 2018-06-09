<template>
  <ul>
    <li v-for="todo in todos" :key="todo.title">{{ todo.title }}</li>
  </ul>  
</template>

<script>
export default {
  data () {
    return {
      todos: [
        { title: 'Todo 1' },
        { title: 'Todo 2' },
        { title: 'Todo 3' },
        { title: 'Todo 4' },
        { title: 'Todo 5' },
        { title: 'Todo 6' },
        { title: 'Todo 7' },
        { title: 'Todo 8' }
      ]
    }
  }
}
</script>

<style>
ul {
  background-color: blue;
}

li {
  list-style-type: none;
}
</style>
