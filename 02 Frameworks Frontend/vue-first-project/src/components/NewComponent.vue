<template>
  <div>
    <h1>Este é um componente novo!</h1>
    <p>{{ text }}</p>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  text: string;
}>();
</script>

<style scoped>
h1 {
  color: red;
}
</style>
