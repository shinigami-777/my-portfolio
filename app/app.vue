<template>
  <div class="pinktheme">
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>

<style>
html, body, #__nuxt, .pink-page {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  background-color:  #ffcfda;
;
  box-sizing: border-box;
}
/* Base pink theme */
.pinktheme {
  background-color: #ffcfda;
  min-height: 100vh;
  width: 100%;
}
</style>

