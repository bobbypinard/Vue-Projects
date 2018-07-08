<template>
  <div class="flag stripes">
    <div class="stars">
      <div class="star" />
    </div>

    <div class="star-stripe"></div>
    <div class="star-tripe"></div>
    <div class="star-stripe"></div>
    <div class="star-tripe"></div>
    <div class="star-stripe"></div>
    <div class="star-tripe"></div>
    <div class="star-stripe"></div>

    <div class="tripe"></div>
    <div class="stripe"></div>
    <div class="tripe"></div>
    <div class="stripe"></div>
    <div class="tripe"></div>
    <div class="stripe"></div>
  </div>
</template>

<style scoped>
.flag {
  height: 24em;
  width: 45em;
  background-color: white;
  margin: auto;
  display: grid;
  grid-template-columns: 2fr 3fr;
}

.stripes {
  display: grid;
  grid-template-rows: repeat(13, 1fr);
}

.stripe {
  background-color: red;
  grid-column: 1 / span 2;
}

.stars {
  grid-column: 1;
  grid-row: 1 / span 7;
  background: blue;

  display: grid;
  grid-template-columns: repeat(9, 1fr)
}

.star-stripe {
  grid-column: 2;
  background-color: red;
}

</style>
