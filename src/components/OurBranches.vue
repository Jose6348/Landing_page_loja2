<template>
  <div id="nossas-filiais" class="nossas-filiais">
    <h2>Nossas Filiais</h2>
    <div class="paises-nossas-filiais">
      <div class="nova-york">
        <img src="../../public/img/City1.png" alt="" />

        <div class="titulo">
          <div class="imagem">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="titulo-imagem">
            <h4>Nova York</h4>
          </div>
        </div>

        <p>
          Explore nossa filial em Nova York, onde o café é mais do que uma bebida, é uma experiência cultural. Venha conhecer nossos baristas especialistas e desfrutar de uma atmosfera única.
        </p>
      </div>
      <div class="texas">
        <img src="../../public/img/City2.png" alt="" />

        <div class="titulo">
          <div class="imagem">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="titulo-imagem">
            <h4>Texas</h4>
          </div>
        </div>

        <p>
          No Texas, nossa filial é o ponto de encontro para amantes de café. Com um ambiente acolhedor e uma seleção de grãos exclusivos, somos o destino perfeito para qualquer hora do dia.
        </p>
      </div>
      <div class="nova-jersey">
        <img src="../../public/img/City3.png" alt="" />

        <div class="titulo">
          <div class="imagem">
            <img src="../../public/img/Rectangle.png" alt="" />
          </div>
          <div class="titulo-imagem">
            <h4>Nova Jersey</h4>
          </div>
        </div>

        <p>
          Situada no coração de Nova Jersey, nossa filial oferece uma variedade de cafés que refletem a diversidade da região. Venha experimentar nosso café artesanal e desfrutar de um momento especial.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NossasFiliais",
};
</script>

<style scoped>
.nossas-filiais {
  display: flex;
  flex-direction: column;
  padding: 4rem;
}

.nossas-filiais h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 4rem;
}

.paises-nossas-filiais {
  display: flex;
  justify-content: space-around;
}

.nova-york,
.texas,
.nova-jersey {
  width: 25%;
  background-color: #253d6b;
  box-shadow: 5px 5px 10px 0px rgb(89, 88, 88);
  margin-bottom: 3rem;
}

.nova-york img,
.texas img,
.nova-jersey img {
  width: 100%;
}

.nova-york h4,
.texas h4,
.nova-jersey h4 {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.5rem;
  color: #fff;
  padding: 1rem 0;
  z-index: 1;
}

.titulo {
  display: flex;
  position: relative;
}

.imagem {
  position: relative;
  top: 1rem;
  left: -1.1rem;
}

.titulo-imagem {
  position: absolute;
  top: 0.7rem;
  left: 1.3rem;
}

.nova-york p,
.texas p,
.nova-jersey p {
  font-family: "Noto Sans", sans-serif;
  font-size: 1rem;
  color: #fff;
  text-align: center;
  line-height: 2rem;
  margin: 1.1rem;
  padding: 1.5rem 1rem;
  background-color: #151a2f;
}
</style>