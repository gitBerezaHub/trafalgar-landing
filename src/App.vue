<template>
  <landing-header />
  <welcome-view />
  <our-services />
</template>

<script setup>
import LandingHeader from '@/components/LandingHeader.vue'
import OurServices from '@/views/OurServices.vue'
import WelcomeView from '@/views/WelcomeView.vue'
</script>

<style lang="scss">
@import "@/styles/reset.css";
#app {
  font-family: Mulish, sans-serif;
}
</style>
