<template>
  <div>
    <button @click="toggleShow">{{ showPrint }}</button>
    <p v-show="show">Hola</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const show = ref(false)
const showPrint = ref('Show')

const toggleShow = () => {
  show.value = !show.value
  if (show.value) showPrint.value = 'Hide'
  else showPrint.value = 'Show'
}
</script>

<style></style>