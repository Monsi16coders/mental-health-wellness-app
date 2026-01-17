<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/breathing">Breathing</RouterLink>
    <RouterLink to="/wellness">Wellness</RouterLink>
    <RouterLink to="/ai-support">AI Support</RouterLink>
  </nav>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>

<style scoped>
nav {
  display: flex;
  gap: 1rem;
  padding: 1rem;
  background: #f0f0f0;
}
nav a {
  text-decoration: none;
  color: #42b983;
}
nav a.router-link-exact-active {
  font-weight: bold;
}
</style>
