<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <div>
      <RouterLink to="/">
        <img src="/Coffe-cafe-logo-by-DEEMKA-STUDIO-4(Creative-Fabrica).jpg" width="200px">
      </RouterLink>
        <h1>COFFEE QUALITY <br>CHALLENGE</h1>

    </div>
    <div class="wrapper">
      <nav>
        <RouterLink to="/" exact-active-class="nav-link-active" active-class="nav-link-active">Home</RouterLink>
        <RouterLink to="/avaliacao" exact-active-class="nav-link-active" active-class="nav-link-active">Avaliação</RouterLink>
        <RouterLink to="/ranking" exact-active-class="nav-link-active" active-class="nav-link-active">Ranking</RouterLink>
      </nav>
    </div>
    <div>
      <img src="/user-icon-on-transparent-background-free-png.webp" alt="" width="130px">
    </div>
  </header>
</template>

<style scoped>
header {
  background-color: white;
  padding: 2vw;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  border: solid 3px #bbbbbb;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
div {
  display: flex;
  align-items: center;
}
nav {
  display: flex;
  gap: 1.5rem;
}

a {
  margin: 0;
  text-decoration: none;
  color: #333;
  font-weight: bold;
  position: relative;
  padding-bottom: 4px;
}

a.nav-link-active {
  color: #8b4513;
}

a.nav-link-active::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 2px;
  background-color: #8b4513;
  border-radius: 2px;
}
</style>
