<template>
  <div class="home-screen">
    <div class="greeting">
      <h1>This is my<br>digital playground</h1>
      <Button text="Stay tuned" />
    </div>
  </div>
</template>

<script lang="ts">
import Button from "~/components/ui/button.vue";
export default {
  name: 'HomeScreenVue',
  components: { Button }
}
</script>

<style scoped>
.home-screen {
  background: #2A2626;
  @apply w-screen h-screen flex justify-center items-center;
}

.greeting {
  @apply text-center;
}

.greeting > h1 {
  @apply mb-10;
}
</style>
