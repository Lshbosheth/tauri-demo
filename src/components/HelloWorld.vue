<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <div class="title">{{msg}}</div>
</template>

<style scoped>
.title {
  font-size: 30px;
}
</style>
