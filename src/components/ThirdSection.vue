<template>
  <div class="terceira-secao">
    <div class="terceira-secao-esquerda">
      <h2>Cafés Quentes</h2>
      <Button />
    </div>

    <div class="terceira-secao-centro">
      <div class="cafe">
        <img class="cafe" src="../../public/img/Coffee3.png" alt="" />
      </div>
      <div class="detalhe">
        <img class="cafe" src="../../public/img/Ellipse.png" alt="" />
      </div>
    </div>
    <div class="terceira-secao-direita">
      <p>
        Descubra o conforto do nosso café quente, perfeito para aquecer sua alma em dias frios. Oferecemos uma gama de sabores que vão desde o tradicional espresso até misturas aromáticas que você vai adorar.
      </p>
    </div>
  </div>
</template>

<script>
import Button from "@/components/MyButton.vue";
export default {
  name: "TerceiraSecao",
  components: {
    Button,
  },
};
</script>

<style scoped>
.terceira-secao {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  background-color: #fefbfa;
  background-image: url("../../public/img/Shape2.png");
  background-repeat: no-repeat;
  background-position: 100%;
  background-size: 57%;
}

.terceira-secao-esquerda {
  width: 350px;
  margin-left: 4rem;
}

.terceira-secao-esquerda h2 {
  width: 350px;
  font-family: "Cormorant Upright", serif;
  font-style: italic;
  color: #1d2440;
  font-size: 6rem;
  line-height: 7rem;
  padding-bottom: 6rem;
}

.terceira-secao-centro {
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  margin-right: 4rem;
}

.cafe {
  position: relative;
  z-index: 1;
}

.detalhe {
  position: absolute;
  z-index: 0;
}

.terceira-secao-direita {
  width: 415px;
}

.terceira-secao-direita p {
  color: #fff;
  font-family: "Noto Sans", sans-serif;
  font-weight: 100;
  text-align: right;
  line-height: 2.2rem;
  margin-right: 4rem;
  font-size: 1rem;
}
</style>