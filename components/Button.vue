<script setup lang="ts">
defineProps({
  color: {
    type: String,
    required: false,
    default: "#2fa",
  },
});
</script>

<template>
  <button :style="{ backgroundColor: color }">
    <!-- Dynamic Content -->
    <slot />
  </button>
</template>
