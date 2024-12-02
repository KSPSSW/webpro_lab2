<template>
  <div>From Input Binding</div>
  <div>{{ text }}</div>
  <input type="text" :value="text" @input="(e) => (text = e.target.value)" />
</template>

<script setup>
import { ref } from 'vue'
const text = ref('Hello')
// const inputText = (e) => (text.value = e.target.value)
</script>
