<template>
  <label for="w">น้ำหนัก</label>
  <input type="text" id="w" v-model.number="w" />
  <label for="kg"> kg.</label>
  <br />
  <label for="h">ส่วนสูง</label>
  <input type="text" id="h" v-model.number="h" />
  <label for="cm"> cm.</label>
  <br />
  {{ w }} {{ h }} <br />
  <button @click="cal">Cal BMI</button><br />
  <label for="BMI">BMI = {{ result }}</label>
</template>

<script setup>
import { ref } from 'vue'
const w = ref(0)
const h = ref(0)
const result = ref(0)
function cal() {
  result.value = w.value / (h.value / 100) ** 2
}
</script>
