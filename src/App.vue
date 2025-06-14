<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>
<template>
  <header class="w-full border-b-2 border-gray-900/10 text-left p-6 mb-8 font-extrabold font-sans text-2xl text-secondary">
        <RouterLink to="/">Authantication with token and cookies</RouterLink>
  </header>
  <RouterView />
  <footer class="w-full border-t-2 border-gray-900/10 text-center p-6 mt-8 font-normal font-sans text-tiny text-primary">
    Copyright 2025.
  </footer>
</template>
<style scoped>
 
</style>
