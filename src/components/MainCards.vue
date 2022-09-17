<script setup>
  import MainCardsSingle from './MainCardsSingle.vue'
</script>

<template>
  <div class="sub-wrapper">
    <MainCardsSingle v-for="n in 20" />
  </div>
</template>

<style scoped lang="postcss">
  .sub-wrapper {
    @apply container mx-auto flex flex-col gap-4 py-4;
  }
</style>