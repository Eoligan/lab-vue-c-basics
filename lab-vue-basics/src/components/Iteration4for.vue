<template>
  <div v-for="item in items" :key="item.id">
    <h2>{{ item.title }}</h2>
    <p>{{ item.description }}</p>
    <p>{{ item.content }}</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const items = ref([
  {
    id: 1,
    title: 'The Dark Knight',
    description: `Movie from the director Christopher Nolan and stars 
    Christian Bale, Heath Ledger, Aaron Eckhart`,
    content: `When the menace known as the Joker wreaks havoc and chaos on the people of Gotham, 
    Batman must accept one of the greatest psychological and physical tests of his ability to fight injustice.`
  },
  {
    id: 2,
    title: 'Memento',
    description: `Movie from the director Christopher Nolan and stars 
    Guy Pearce, Carrie-Anne Moss, Joe Pantoliano`,
    content: `A man with short-term memory loss attempts to track down his wife's murderer.`
  },
  {
    id: 3,
    title: 'Inception',
    description: `Movie from the director Christopher Nolan and stars 
    Leonardo DiCaprio, Joseph Gordon-Levitt, Elliot Page`,
    content: `A thief who steals corporate secrets through the use of dream-sharing technology
     is given the inverse task of planting an idea into the mind of a C.E.O., but his tragic past
     s may doom the project and his team to disaster.`
  }
])
</script>

<style></style>
