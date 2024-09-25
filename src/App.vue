<template>
  <landing-header />
  <welcome-view />
</template>

<script setup>
import LandingHeader from '@/components/LandingHeader.vue'
import WelcomeView from '@/components/WelcomeView.vue'
</script>

<style lang="scss">
@import "@/styles/reset.css";
#app {
  font-family: Mulish, sans-serif;
}
</style>
