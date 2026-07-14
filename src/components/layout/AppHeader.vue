<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <h1>COFFEE QUALITY <br>CHALLENGE</h1>
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
header {
  background-color: white;
  padding: 2vw;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  border: solid 2px #9e9e9e;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
