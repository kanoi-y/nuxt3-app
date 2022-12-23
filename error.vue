<template>
  <NuxtLayout>
    <p>{{ error }}</p>
    <button @click="clearError({ redirect: '/' })">Clear Error</button>
  </NuxtLayout>
</template>

<script setup>
const props = defineProps({
  error: Object,
});
</script>
