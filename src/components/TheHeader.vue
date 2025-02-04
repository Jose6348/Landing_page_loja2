<template>
  <div id="cabecalho" class="cabecalho">
    <Navbar />
    <div class="informacoes-cabecalho">
      <h1>Café</h1>
      <h3>Tudo o que você ama no café</h3>
      <p>
        Descubra a arte do café, desde métodos de preparo tradicionais até inovações que encantam. <br />
        Cada xícara é uma experiência única, perfeita para começar o seu dia ou para um momento de pausa.
      </p>
    </div>
    <Button class="btn-cabecalho" />
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Button from "./MyButton.vue";
export default {
  components: {
    Navbar,
    Button,
  },
};
</script>

<style scoped>
.cabecalho {
  width: 100%;
  background-image: url("../../public/img/Background.png");
  background-position: 100%;
  background-repeat: no-repeat;
}

.informacoes-cabecalho {
  width: 800px;
  margin-left: 4rem;
}

.informacoes-cabecalho h1 {
  font-family: "Cormorant Upright", serif;
  font-weight: 100;
  font-style: italic;
  color: #1d2440;
  font-size: 9rem;
}

.informacoes-cabecalho h3 {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
  color: #ff540e;
  font-size: 2rem;
  margin-top: 4rem;
}

.informacoes-cabecalho p {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
  color: #1d2440;
  font-size: 0.9rem;
  margin-top: 2rem;
}

.btn-cabecalho {
  margin: 3.6rem 4rem;
}
</style>