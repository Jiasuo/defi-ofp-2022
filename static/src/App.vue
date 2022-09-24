<script setup>
import TopBar from './components/TopBar.vue';
import HomeServices from './components/HomeServices.vue';
import HomePortfolio from './components/HomePortfolio.vue';
import HomeTestimonials from './components/HomeTestimonials.vue';
import HomeBlog from './components/HomeBlog.vue';
import HomeContact from './components/HomeContact.vue';

</script>

<template>
  <TopBar />
  <main>
    <HomeHeader />
    <HomeServices />
    <HomePortfolio />
    <HomeTestimonials />
    <HomeBlog />
    <HomeContact />
  </main>
</template>

<style scoped>  
</style>
