<script setup lang="ts">
const name = import.meta.env.VITE_AGENT_NAME;
</script>

<template>
  <div class="about">
    <h1>This is an about page - {{ name }} </h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
