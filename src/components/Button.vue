<template>
  <div id="mine-button">
    <button>{{ message }}{{ type }}</button>
  </div>
</template>

<script setup>
defineProps({
  message: String,
  type: {
    type: String,
    default: "primary",
  },
});
</script>

<style scoped>
.mine-button {
  display: flex;
}
</style>
