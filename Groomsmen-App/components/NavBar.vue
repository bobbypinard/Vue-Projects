<template>
  <div class="nav">
    <div v-for="item in items" :key="item.title" class="item">
      <span >{{ item.title }}</span>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {title: 'This is the title.'}
      ]
    }
  }
}
</script>