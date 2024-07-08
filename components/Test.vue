<script setup lang="ts">
interface Props {
  name?: string;
}
defineProps<Props>();
const { data } = useFetch("https://rickandmortyapi.com/api/character")
</script>
<template>
  <pre>{{ data }}</pre>
  {{ name }}
</template>
