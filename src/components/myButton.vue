<template>
  <button :class="color">{{ text }}</button>
</template>

<style scoped>
button {
  padding: 6px 35px;
  cursor: pointer;
  border-radius: 5px;
  background-color: transparent;
  font-weight: 500;
}
.red:hover {
  color: var(--primary-soft-red);
  border-color: var(--primary-soft-red);
}
.blue:hover {
  color: var(--primary-soft-blue);
  border-color: var(--primary-soft-blue);
}
.gray:hover {
  color: var(--primary-soft-gray);
  border-color: var(--primary-soft-gray);
}
</style>

<script setup>
defineProps({
  text: String,
  color: String,
});
</script>
