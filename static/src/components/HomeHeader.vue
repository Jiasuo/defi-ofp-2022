<script setup>
import HomeHeaderHero from './HomeHeaderHero.vue';
import HomeHeaderClients from './HomeHeaderClients.vue';
import HomeHeaderTopBar from './HomeHeaderTopBar.vue';  
</script>

<template>
  <section class="homeHeaderContainer">
    <HomeHeaderTopBar />
    <HomeHeaderHero />
    <HomeHeaderClients />
  </section>
</template>

<style scoped>
  .homeHeaderContainer{
    background: var(--black);
  }
</style>