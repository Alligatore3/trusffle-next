<script setup lang="ts">
useHead({
  bodyAttrs: {
    class:
      'bg-background-light dark:bg-background-dark font-display text-text-main antialiased selection:bg-primary selection:text-primary-content',
  },
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
