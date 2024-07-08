<script setup lang="ts">
import {ref} from "vue";

defineProps<{
  text?: string;
}>();
const counter = ref(0)
</script>
<template>
  {{ text }}
  <p @click="counter++">lösakdlsöakdlö {{ counter }}</p>
</template>
