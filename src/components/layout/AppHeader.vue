<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <div>
      <img src="../../../public/Coffe-cafe-logo-by-DEEMKA-STUDIO-4(Creative-Fabrica).jpg" width="200px">
      <h1>COFFEE QUALITY <br>CHALLENGE</h1>
    </div>
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
div {
  display: flex;
  align-items: center;
}
</style>
