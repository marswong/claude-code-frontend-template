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
</style>
