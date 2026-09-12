<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>

  <p>
    Deploying a Vue 3 + Vite + TypeScript + TailwindCSS project to the subject Management of Software Configuration course. This project is a simple example of a Vue 3 component that displays a message.
  </p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
