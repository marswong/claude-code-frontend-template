<template>
  <div class="flex justify-between items-center">
    <a href="https://vite.dev" target="_blank">
      <img src="./assets/vite.svg" class="logo" alt="vite logo" />
    </a>
    <a href="https://vuejs.org" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="vue logo" />
    </a>
    <a href="https://daisyui.com" target="_blank">
      <img src="./assets/daisyui.svg" class="logo daisyui" alt="daisyui logo" />
    </a>
    <a href="https://github.com/vercel/serve" target="_blank">
      <img src="/serve.svg" class="logo serve" alt="serve logo" />
    </a>
  </div>
  <HelloWorld msg="vite + vue + daisyui + serve" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue';
</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.logo.daisyui:hover {
  filter: drop-shadow(0 0 2em #FFD819aa);
}

.logo.serve:hover {
  filter: drop-shadow(0 0 2em #000000aa);
}
</style>
