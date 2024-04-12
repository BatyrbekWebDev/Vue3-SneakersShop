<script setup>
import { ref } from 'vue'

const count = ref(0)
const increment = () => {
  count.value++
}
</script>

<template>
  <h1>{{ count }}</h1>
  <button @click="increment">+</button>
  <h1>Hello</h1>
  <h2>Что то изменили</h2>
  <h2>Еще что то изменили</h2>
  <h2>Еще что то изменили</h2>
  <h2>Еще что то изменили</h2>
</template>

<style scoped></style>
