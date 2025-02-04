<template>
  <div id="segunda-secao" class="segunda-secao">
    <div class="segunda-secao-esquerda">
      <p>
        Desfrute dos nossos cafés gelados, perfeitos para dias quentes ou quando você está precisando de um refresco. Nossa seleção inclui desde clássicos como o Cold Brew até inovações que surpreenderão seu paladar.
      </p>
    </div>

    <div class="segunda-secao-centro">
      <div class="cafe">
        <img class="cafe" src="../../public/img/Coffee2.png" alt="" />
      </div>
      <div class="detalhe">
        <img class="cafe" src="../../public/img/Ellipse.png" alt="" />
      </div>
    </div>
    <div class="segunda-secao-direita">
      <h2>Cafés Gelados</h2>
      <Button />
    </div>
  </div>
</template>

<script>
import Button from "@/components/MyButton.vue";
export default {
  name: "SegundaSecao",
  components: {
    Button,
  },
};
</script>

<style scoped>
.segunda-secao {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  background-color: #fefbfa;
  background-image: url("../../public/img/Shape1.png");
  background-repeat: no-repeat;
  background-size: 53%;
}

.segunda-secao-esquerda {
  width: 415px;
}

.segunda-secao-esquerda p {
  color: #fff;
  font-family: "Noto Sans", sans-serif;
  font-weight: 100;
  text-align: left;
  line-height: 2.2rem;
  margin-left: 4rem;
  font-size: 1rem;
}

.segunda-secao-centro {
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  margin-right: 3rem;
}

.cafe {
  position: relative;
  z-index: 1;
}

.detalhe {
  position: absolute;
  z-index: 0;
}

.segunda-secao-direita {
  width: 350px;
  margin-right: 4rem;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.segunda-secao-direita h2 {
  width: 350px;
  font-family: "Cormorant Upright", serif;
  font-style: italic;
  color: #1d2440;
  font-size: 6rem;
  line-height: 6.5rem;
  text-align: right;
  padding-bottom: 6rem;
}
</style>