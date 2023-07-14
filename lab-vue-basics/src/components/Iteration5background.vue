<template>
  <button @click="toggleColor">Change background color</button>
</template>

<script setup>
import { ref } from 'vue'

const styleBackground = ref('white')
const toggleColor = () => {
  if (styleBackground.value === 'red') {
    styleBackground.value = 'white'
  } else styleBackground.value = 'red'

  document.body.style.backgroundColor = styleBackground.value
}
</script>

<style></style>
