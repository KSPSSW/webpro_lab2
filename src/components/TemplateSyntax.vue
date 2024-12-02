<script setup>
var msg = 'Hello Message'
var rawHtml = '<h1>Hello</h1>'
</script>

<template>
  <div>{{ msg }}</div>
  <div v-html="rawHtml"></div>
</template>
