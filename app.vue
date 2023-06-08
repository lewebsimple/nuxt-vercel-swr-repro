<script setup lang="ts">
const {data: timestamp} = await useAsyncData(async () => {
  return new Date().toString();
})
</script>

<template>
  <div>
    {{  timestamp  }}
  </div>
</template>
