<template>
  <div>From Input Binding</div>
  <div>{{ text }}</div>
  <input v-model="text" />

  <span>Multiline message is:</span>
  <p style="white-space: pre-line">{{ message }}</p>
  <textarea v-model="message" placeholder="add multiple lines"></textarea>

  <input type="checkbox" id="checkbox" v-model="checked" />
  <label for="checkbox">{{ checked }}</label>

  <div>Checked names: {{ checkedNames }}</div>

  <input type="checkbox" id="jack" value="Jack" v-model="checkedNames" />
  <label for="jack">Jack</label>

  <input type="checkbox" id="john" value="John" v-model="checkedNames" />
  <label for="john">John</label>

  <input type="checkbox" id="mike" value="Mike" v-model="checkedNames" />
  <label for="mike">Mike</label>
</template>

<script setup>
import { ref } from 'vue'
const text = ref('Hello')
const message = ref('')
const checked = ref(true)
const checkedNames = ref([])
</script>
