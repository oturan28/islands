<script setup lang="ts">
interface Props {
  name?: string;
}
defineProps<Props>();
const { data } = await useFetch("https://rickandmortyapi.com/api/character")
const counter = ref(0)
</script>
<template>
  <p @click="counter++">öaslkdlösakdölsakdölsad {{ counter }}</p>
  <pre>{{ data }}</pre>
  {{ name }}
</template>
