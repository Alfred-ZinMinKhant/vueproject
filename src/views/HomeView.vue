<script setup>
import Hero from "@/components/Hero.vue";
import Homecard from "@/components/HomeCard.vue";
import JobListings from "@/components/JobListings.vue";
</script>
<template>
  <Hero />
  <Homecard />
  <JobListings :limit="3" :showbutton="true" />
</template>
