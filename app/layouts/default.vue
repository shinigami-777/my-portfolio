<template>
  <div>
    <Navbar />
    <div id="app">
      <Nuxt />
    </div>
  </div>
</template>

<script setup>
import Navbar from '~/components/Navbar.vue'
</script>

<style scoped>
#app {
  margin-top: 100px;

}
</style>
