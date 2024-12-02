<script setup>
import Hello from './components/HelloComponent.vue'
import TemplateSyntax from './components/TemplateSyntax.vue'
import ReactiveFundamentals from './components/ReactiveFundamentals.vue'
import FormInputBinding from './components/FormInputBinding.vue'
import HelloMyName from './components/HelloMyName.vue'
import MyPlus from './components/MyPlus.vue'
</script>

<template>
  <MyPlus></MyPlus>
  <hr />
  <HelloMyName></HelloMyName>
  <hr />
  <FormInputBinding></FormInputBinding>
  <hr />
  <ReactiveFundamentals></ReactiveFundamentals>
  <hr />
  <div>Hello</div>
  <hr />
  <span><Hello></Hello></span>
  <hr />
  <TemplateSyntax></TemplateSyntax>
  <hr />
</template>

<style scoped></style>
