<template>
  <div class="container">
    <div class="flag">
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
      <div class="stripe" />
    </div>
  </div>
</template>

<style scoped>
.container {
  background-color: rgb(158, 210, 255);
  min-height: 100vh;
}

.flag {
  height: 26em;
  width: 45em;
  background-color: white;
  margin: auto;
  display: grid;
  grid-template-rows: repeat(2, 1fr);
  grid-template-columns: 1fr, 3fr;
  grid-template-areas: 
}

.stripe {
  height: 2em;
  background-color: red;
}
</style>
