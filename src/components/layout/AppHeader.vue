<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/avaliacao">Avaliação</RouterLink>
        <RouterLink to="/ranking">Ranking</RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
</style>
