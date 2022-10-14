<template>
  <button :style="{ background: color }">
    <div>
      <h1>Use o meu component</h1>
    </div>
    <slot />
  </button>
</template>

<script setup lang="ts">
defineProps({
  color: {
    type: String,
    required: false,
    default: '#2fa'
  }
})
</script>

<style scoped lang="scss"></style>
