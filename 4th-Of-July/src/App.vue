<template>
  <div id="app">
    <flag />
  </div>
</template>

<script>
import Flag from './components/Flag'

export default {
  name: 'App',
  components: {
    Flag
  }
}
</script>

<style>
#app {
  background-color: rgb(158, 210, 255);
  min-height: 100vh;
  margin: -8px;
}
</style>
