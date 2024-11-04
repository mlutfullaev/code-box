<script lang="ts" setup>
const search = ref('')
</script>

<template>
  <main class="flex items-center justify-center h-screen">
    <input
      v-model="search"
      type="text"
      placeholder="Search for a component"
      class="bg-transparent border-primary border border-solid rounded-md py-2 px-4 text-xl w-[400px] mx-auto text-primary"
    >
  </main>
</template>

<style lang="scss" scoped>

</style>
