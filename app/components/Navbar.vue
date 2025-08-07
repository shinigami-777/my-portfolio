<template>
  <nav class="navbar">
    <ul class="nav-links">
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/projects">Projects</NuxtLink></li>
      <li><NuxtLink to="/experience">Experience</NuxtLink></li>
      <li><NuxtLink to="/blog">Blog</NuxtLink></li>
    </ul>
  </nav>
</template>

<style scoped>
.navbar {
  width: 100%;
  max-width: 800px;
  margin: 20px auto;
  text-align: center;
  padding: 15px 0;
  background-color:rgba(202, 27, 94, 0.53);
  border-radius: 12px;
  box-shadow: 0 0 10px #rgb(0, 0, 0), 0 0 20px #0ff inset;
}

.nav-links {
  display: flex;
  justify-content: center;
  gap: 50px;
  margin: 0;
  padding: 0;
}

.nav-links li a {
  font-family: monospace;
  font-size: 20px;
  color: rgba(36, 7, 68, 0.85);
  text-decoration: none;
  text-shadow: 1px 0 purple, 0 1px purple, -1px 0 purple, 0 -1px purple; /* fake bold */
  transition: color 0.2s ease, text-shadow 0.2s ease;
}
.nav-links li a:hover {
  color: white;
  text-shadow: 1px 0 white, 0 1px white, -1px 0 white, 0 -1px white;
}
</style>