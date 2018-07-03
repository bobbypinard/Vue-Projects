<template>
  <section class="container">
    <h1 class="title">
      Avril Lavigne
    </h1>
    <div class="videos">
      <card v-for="vid in vids" :key="vid.title" :title="vid.title" :link="vid.link"/>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Card from '~/components/Card.vue'

export default {
  components: {
    Card
  },
  data () {
    return {
      title: 'testing',
      vids: [
        {
          title: 'Blah',
          link: ''
        },
        {
          title: 'Blergh',
          link: ''
        },
        {
          title: 'Bluh',
          link: ''
        },
        {
          title: 'Bluff',
          link: ''
        }
      ]
    }
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  text-align: center;
  background-color: black;
  color: #f700d6;
}

.title {
  font-weight: 300;
  font-size: 100px;
  color: #ff40e5;
  margin-bottom: .5em;
}
</style>
