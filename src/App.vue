<script setup>
import Hello from './components/HelloComponent.vue'
import TemplateSyntax from './components/TemplateSyntax.vue'
import ReactiveFundamentals from './components/ReactiveFundamentals.vue'
import FormInputBinding from './components/FormInputBinding.vue'
</script>

<template>
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
