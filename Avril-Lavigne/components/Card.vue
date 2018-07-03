<template>
  <!--  https://www.youtube.com/playlist?list=PLInqE8AnCFQW_HGGquwAjyqA0rqEWrH1x  -->
  <div class="card">
    <h1>{{ title }}</h1>
    <span>{{ link }}</span>
  </div>
</template>

<script>

export default {
  props: {
    title: String,
    link: String
  } 
}
</script>


<style scoped>
.card {
  margin: auto;
  margin-bottom: 1em;
  background-color: #bb00a2;
  height: 9em;
  width: 21em;
  color: cyan;
  animation-name: card;
  animation-duration: 2s;
}

@keyframes card {
  0% {
    background-color: blue;
  }
  100% {
    background-color: #bb00a2;
  }

}
</style>
