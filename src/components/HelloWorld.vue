<template>
  <h1>{{ msg }}</h1>
</template>
<script setup lang="ts">
import { ref } from "vue";
defineProps<{ msg: string }>();
</script>
<style scoped>
.read-the-docs {
  color: #888888;
}
</style>
