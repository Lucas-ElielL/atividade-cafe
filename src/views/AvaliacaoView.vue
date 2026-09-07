<script setup>
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
