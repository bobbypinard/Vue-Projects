<template>
  <ul>
    <li v-for="todo in todos" :key="todo.title">{{ todo.title }} <span>&nbsp;X</span> </li>
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
  //background-color: purple;
  text-align: center;
  padding-top: 5em;
}

li {
  list-style-type: none;
  font-size: 2em;
  margin-bottom: 1em;
}
</style>
