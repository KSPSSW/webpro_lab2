<template>
  <div>From Input Binding</div>
  <div>{{ text }}</div>
  <input type="text" :value="text" @input="inputText" />
</template>

<script setup>
import { ref } from 'vue'
const text = ref('Hello')
const inputText = (e) => {
  console.log(e.target.value)
  text.value = e.target.value
}
</script>
