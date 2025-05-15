<script setup lang="ts">
import { onMounted } from 'vue'

onMounted(() => {
  window.location.href = 'https://augustocuginotti.com'
})
</script>

<template>
  <main class="flex flex-col justify-center">
    <HomeTwitter />
    <HomeHero />
    <HomeFeatures />
    <HomeLogos />
    <HomeCta />
  </main>
</template>
