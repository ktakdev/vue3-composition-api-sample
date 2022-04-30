<script setup lang="ts">
export interface TextFormProps {
  value?: string;
}

defineProps<TextFormProps>()
</script>

<template>
  <div class="text-form">
    <input type="text" :value="value" />
  </div>
</template>
