<template>
  <ul>
    <li v-for="todo in todos" :key="todo.title"><a @click="deleteTodo(todo.title)">X</a> <i class="fas fa-trash-alt"></i> {{ todo.title }}</li>
  </ul>  
</template>

<script>
export default {
  data () {
    return {
      todos: [
        { title: 'Reserve Lakehouse' },
        { title: 'Rent Boat' },
        { title: 'Buy fishing licenses' }
      ]
    }
  },
  methods: {
    deleteTodo: function (item) {
      this.todos.splice(item, 1);
      console.log("Deleted ", item);
    }
  }
}
</script>

<style>
a {
  font-size: 1em;
  font-family: 'Dancing Script';
  color: silver;
}

ul {
  text-align: left;
  padding: 2em, 0, 2em, 0;
}

li {
  list-style-type: none;
  font-size: 2em;
  font-family: 'Dancing Script';
  padding-bottom: 1em;
}
</style>
