<script setup>

</script>

<template>
  <main>
    <section class="banner">
      <div class="esquerdaBanner">
        <img src="/Coffe-cafe-logo-by-DEEMKA-STUDIO-4(Creative-Fabrica).jpg">
      </div>
      <div class="direitaBanner">
        <h2>Campeonato de Avaliação <br> de Qualidade de Café</h2>
        <p>
          Avalie, compare e descubra os melhores <br> cafés especiais.
        </p>
      </div>
    </section>
    <section class="feed">
      <div>
        <h3>Total de Cafés Avaliados</h3>
        <span class="numeros">12</span>
        <p>cafés</p>
      </div>
      <div>
        <h3>Café com a Maior Nota</h3>
        <span class="numeros">9.3</span>
        <p><span>Bourboun Amarelo</span></p>
        <p>Fazenda Boa Vista</p>
      </div>
      <div>
        <h3>Última Avaliação</h3>
        <span class="numeros">8.7</span>
        <p>
          <span>Arara</span>
        </p>
        <p>25/05/2025 14:32</p>
      </div>
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
.banner {
  background-color: rgb(255, 241, 236);
  padding: 2vw 14vw;
  border-radius: 20px;
  border: solid 3px #bbbbbb;;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 1vw 0;
}
.banner img {
  border-radius: 30px;
  border: solid 3px #9e9e9e;
  width: 500px;
}
.banner h2 {
  font-size: 3rem;
  border-bottom: solid 5px rgb(165, 132, 42);
  padding: 5px 10px 15px 10px;
  text-align: center;
}
.banner .direitaBanner p {
  font-size: 1.5rem;
  text-align: center;
}
.feed {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 2vw;
  margin: 2vw 0;
}
.feed div {
  border: solid 3px #bbbbbb;
  border-radius: 20px;
  text-align: center;
  padding: 20px;
}
.feed h3 {
  font-weight: 500;
  font-size: 1.3rem;
}
.feed div p {
  font-size: 1.2rem;
}
.feed div span {
  font-size: 1.7rem;
  font-weight: 400px;
  color: #021229;
}
.feed div .numeros {
  font-size: 3rem;
  font-weight: bold;
  color:brown;
}
</style>
