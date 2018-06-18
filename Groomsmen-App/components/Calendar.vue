<template>
  <div class="Calendar">
    <h1 class="date">{{ date }}</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      date: 'May 3'
    }
  }
}
</script>


<style scoped>
h1.date {
  font-family: 'Dancing Script';
}
</style>
