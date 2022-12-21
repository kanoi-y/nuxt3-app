<template>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>
<script setup>
const enableCustomLayout = () => {
  setPageLayout("custom");
};
definePageMeta({
  layout: false,
});
</script>
