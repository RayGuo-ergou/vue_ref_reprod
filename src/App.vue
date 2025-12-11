<script setup lang="ts">
import { ref } from 'vue';

const foo = ref<HTMLDivElement|null>(null)
</script>

<template>
  <div ref="foo"></div>
</template>

<style scoped></style>
