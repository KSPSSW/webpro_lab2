<template>
  <div>
    <label for="num1">num1</label>
    <input type="text" id="num1" v-model="num1" />
    <label for="num2">num2</label>
    <input type="text" id="num2" v-model="num2" />
    =
    {{ num1 + num2 }}
  </div>
</template>

<script setup>
import { ref } from 'vue'
const num1 = ref(0)
const num2 = ref(0)
</script>
