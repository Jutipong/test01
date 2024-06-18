<script setup lang="ts">
const port = import.meta.env.VITE_PORT
const name = import.meta.env.VITE_APP_NAME
</script>

<template>
  <div>
    <h1>Port: {{ port }}</h1>
    <h1>Name: {{ name }}</h1>
  </div>
</template>