<template>
  <div class="image" v-editable="blok">
    <img v-bind:src="blok.image" v-bind:alt="blok.name">
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>

<style>
.image img {
  width: 10vw;
  height: 10vh;
}
</style>
