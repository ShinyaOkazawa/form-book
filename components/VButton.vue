<template>
  <button class="button">
    <slot />
  </button>
</template>

<style scoped>
.button {
  min-width: 120px;
  padding: var(--space-8);
}
</style>
