<template>
  <header class="flex justify-between items-center h-16">
    <RouterLink to="/">
      <img alt="Vue logo" class="logo" src="./assets/vue.svg" />
    </RouterLink>

    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<style scoped>
.logo {
  cursor: pointer;
}

nav a.router-link-exact-active {
  color: #41B883;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

nav a:hover {
  color: #41B883;
}
</style>
