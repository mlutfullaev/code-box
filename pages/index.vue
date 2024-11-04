<script lang="ts" setup="">
definePageMeta({
  title: 'CodeBOX'
})
</script>

<template>
  <main class="h-screen bg-primary flex items-center justify-center gap-10 flex-col">
    <h1 class="text-white text-center text-4xl">CodeBOX</h1>
    <router-link
      to="/components"
      class="bg-white py-2 px-10 rounded text-primary"
    >
      Go to components
    </router-link>
  </main>
</template>

<style lang="scss" scoped>

</style>