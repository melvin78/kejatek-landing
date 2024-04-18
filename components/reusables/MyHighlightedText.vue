<script setup>
const props = defineProps({
  text: String,
  link: String,
});
</script>

<template>
  <span
    class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-teal-400"
    >{{ props.text }}
  </span>
</template>

<style scoped></style>
