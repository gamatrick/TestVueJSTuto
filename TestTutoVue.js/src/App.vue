<script setup>
import {ref} from 'vue'

const todolist = ref ({
  title: 'Tâche à faire',
  completed: false,
  date: 1020302103
})

</script>

<template>
  
  <ul>
    <li>{{ todolist.title }}</li>
  </ul>

</template>