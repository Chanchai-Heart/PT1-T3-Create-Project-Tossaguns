<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <main>
      <Navbar class="sticky top-0 z-[1]" />
    <RouterView />
  </main>
</template>
