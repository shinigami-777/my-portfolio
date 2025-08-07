<template>
  <div>
    <Navbar />
    <div id="app">
      <NuxtPage />
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
