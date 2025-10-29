<template>
  <div class="flex flex-col items-center">
    <div class="flex justify-between items-center">
      <a href="https://vite.dev" target="_blank">
        <img src="../assets/vite.svg" class="logo" alt="vite logo" />
      </a>
      <a href="https://vuejs.org" target="_blank">
        <img src="../assets/vue.svg" class="logo vue" alt="vue logo" />
      </a>
      <a href="https://tailwindcss.com" target="_blank">
        <img src="../assets/tailwindcss.svg" class="logo tailwindcss" alt="tailwindcss logo" />
      </a>
      <a href="https://github.com/vercel/serve" target="_blank">
        <img src="/serve.svg" class="logo serve" alt="serve logo" />
      </a>
    </div>
    <h1 class="text-4xl">{{ msg }}</h1>
    <p class="read-the-docs">Click on the logos to learn more</p>
  </div>
</template>

<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<style scoped>
.logo {
  height: 8em;
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

.logo.tailwindcss:hover {
  filter: drop-shadow(0 0 2em #38bdf8aa);
}

.logo.serve:hover {
  filter: drop-shadow(0 0 2em #000000aa);
}

.read-the-docs {
  margin-top: 16px;
  color: #888;
}
</style>
