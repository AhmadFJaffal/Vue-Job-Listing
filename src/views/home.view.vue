<script setup>
import Hero from '@/components/hero.vue'
import HomeCards from '@/components/home-cards.vue'
import JobListings from '@/components/job-listings.vue'
</script>

<template>
  <Hero title="Become a Vue Dev" subtitle="Find the Vue job that fits your skills" />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
