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
</template>

<style scoped></style>
