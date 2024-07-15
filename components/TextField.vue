<script setup lang="ts">
defineProps({
  id: {
    type: String,
    required: true,
  },
  label: {
    type: String,
    required: true,
  },
  hint: {
    type: String,
    default: "",
  },
  type: {
    type: String,
    default: 'text'
  }
});
</script>

<template>
  <div>
    <label :for="id">
      <span class="label">{{ label }}</span>
      <span v-if="hint" class="hint">{{ hint }}</span>
    </label>
    <VInput :id="id" :name="id" :type="type" />
  </div>
</template>

<style scoped>
label {
  font-size: var(--text-size-normal);
}

.label {
  display: block;
  margin-bottom: var(--space-4);
  font-weight: bold;
}

.hint {
  display: block;
  margin-bottom: var(--space-4);
}
</style>
