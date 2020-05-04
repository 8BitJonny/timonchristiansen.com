<template>
  <button class="standard-button">{{ text }}</button>
</template>

<script lang="ts">
export default {
  name: 'Button',
  props: {
    text: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.standard-button {
  color: #2A2626;
  font-size: 1.2rem;
  background-color: white;
  padding: 0.8rem 1.6rem;
  border-radius: 1.5rem;
  @apply outline-none select-none;
}
</style>
