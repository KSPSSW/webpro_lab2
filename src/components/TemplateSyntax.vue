<script setup>
var msg = 'Hello Message'
var rawHtml = '<h1>Hello</h1>'
var myId = 'myId1'
var color = 'blue'
var isDisable = false
var objectOfAttrs = {
  id: 'container',
  class: 'wrapper',
  style: 'background-color:green',
}
var number = 20
var ok = true
</script>

<template>
  <div>{{ msg }}</div>
  <div v-html="rawHtml"></div>
  <div :id="myId"></div>
  <font :color="color">Red</font>
  <button :disabled="isDisable">isEnable</button>
  <div v-bind="objectOfAttrs">Background green</div>
  <div>{{ number + 1 }}</div>
  <div>{{ ok ? 'Yes' : 'No' }}</div>
</template>
