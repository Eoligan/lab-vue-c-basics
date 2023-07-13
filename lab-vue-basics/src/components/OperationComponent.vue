<template>
  <div>
    <p>{{ 2 + 2 }}</p>
    <p>Function: {{ getString() }}</p>
  </div>
</template>

<script setup>
import { ref, computed } from 'vue'

const author = ref({
  name: 'John Doe',
  books: ['Vue 2 - Advanced Guide', 'Vue 3 - Basic Guide', 'Vue 4 - The Mystery']
})

const getString = computed(() => {
  return `${author.value.name} has these books:` // ${author.value.books}`
})
</script>

<style scoped></style>
