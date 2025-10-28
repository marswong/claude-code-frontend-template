<template>
  <h1 class="text-4xl">{{ msg }}</h1>

  <div class="p-8">
    <button type="button" class="btn btn-neutral btn-outline mb-2" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p class="read-the-docs">Click on the logos to learn more</p>
</template>

<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
})

const count = ref(0);
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
