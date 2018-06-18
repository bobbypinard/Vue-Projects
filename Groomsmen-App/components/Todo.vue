<template>
  <ul>
    <li v-for="todo in todos" :key="todo.title">{{ todo.title }} <button @click="deleteTodo(todo.title)">X</button> </li>
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
        { title: 'Todo 8' },
        { title: 'Todo 9' },
        { title: 'Todo 10' },
        { title: 'Todo 11' },
        { title: 'Todo 12' },
        { title: 'Todo 13' },
        { title: 'Todo 14' }
      ]
    }
  },
  methods: {
    deleteTodo: function (message) {
      console.log("Deleted")
    }
  }
}
</script>

<style>
ul {
  text-align: center;
  padding: 2em, 0, 2em, 0;
}

li {
  list-style-type: none;
  font-size: 2em;
  font-family: 'Dancing Script';
  padding-bottom: 1em;
}
</style>
