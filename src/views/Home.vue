<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <h1>Welcome to the Mental Health & Wellness Companion</h1>
    <p>This is the Home page placeholder.</p>
    <nav>
      <RouterLink to="/breathing">Breathing</RouterLink>
      <RouterLink to="/wellness">Wellness</RouterLink>
      <RouterLink to="/ai-support">AI Support</RouterLink>
    </nav>
  </header>
</template>

<style scoped>
header {
  text-align: center;
  padding: 2rem;
}
nav {
  margin-top: 1rem;
}
nav a {
  margin: 0 1rem;
  text-decoration: none;
  color: #42b983;
}
</style>
