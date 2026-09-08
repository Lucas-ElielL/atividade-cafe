<script setup>
import { cafes } from '@/data/cafes';
</script>
<template>
  <main>
    <section class="avaliar">
    <h3>Nova Avaliação</h3>
    <form action="avaliar">
      <label for="nome">
        Nome do Café
      </label>
      <input type="text" id="nome">
      <label for="produtor">
        Produtor
      </label>
      <input type="text" id="produtor">
      <label for="aroma">
        Aroma
      </label>
        <input type="number" id="aroma">
      <label for="sabor">
        Sabor
      </label>
      <input type="number" id="sabor">
      <label for="acidez">
        Acidez
      </label>
      <input type="number" id="acidez">
      <label for="corpo">
        Corpo
      </label>
      <input type="number" id="corpo">
      <label for="finalizacao">
        Finalização
      </label>
      <input type="number" id="finalizacao">
      <p>Média Calculada: 0.0</p>
      <button type="submit">Salvar Avaliação</button>
    </form>
  </section>
  <section>
    <h3>Cafés avaliados</h3>
    <p>Total de registros: {{ cafes.length }}</p>
    <ul>
      <li v-for="cafe in cafes" :key="cafe.id">
        <h4>Nome: {{ cafe.nome }}</h4>
        <p><span>Produtor: {{ cafe.produtor }}</span></p>
        <p>Aroma: {{ cafe.aroma }}</p>
        <p>Doçura: {{ cafe.docura }}</p>
        <p>Acidez: {{ cafe.acidez }}</p>
        <p>Corpo: {{ cafe.corpo }}</p>
        <p>Finalização: {{ cafe.finalizacao }}</p>
      </li>
    </ul>
  </section>
  </main>
</template>
<style scoped>
main {
  border: solid 3px #bbbbbb;
  border-top: 0px;
  background-color: white;
  padding: 1vw 2vw;
}
main form {
  display: flex;
  flex-direction: column;
}
</style>

