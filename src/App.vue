<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './views/Home.vue'

export default {
  name: 'app',
  components: {
    Home,
  }
}
</script>

<style>
 body, html {
   font-family: 'Quicksand', sans-serif;
    margin: 0;
    padding: 0;
 }
</style>
