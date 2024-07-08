<script setup lang="ts">
interface Props {
  name?: string;
}
defineProps<Props>();
</script>
<template>
  {{ name }}
</template>
