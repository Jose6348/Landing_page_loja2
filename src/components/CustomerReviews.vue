<template>
  <div id="depoimentos-clientes" class="depoimentos-clientes">
    <h2>Depoimentos de Clientes</h2>
    <div class="depoimentos-clientes-info">
      <div class="depoimentos-clientes-info-img">
        <img src="../../public/img/People.png" alt="" />
      </div>
      <div class="depoimentos-clientes-info-texto">
        <div class="depoimentos-clientes-info-texto-1">
          <h3>João Pedro</h3>
          <p>
            Adoro este produto! Facilitou muito minha vida e me ajudou a economizar tempo. Recomendo para todos!
          </p>
        </div>

        <div class="depoimentos-clientes-info-texto-2">
          <h3>Elisa Thomaz</h3>
          <p>
            Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DepoimentosClientes.vue",
};
</script>

<style scoped>
.depoimentos-clientes {
  display: flex;
  flex-direction: column;
  padding: 4rem;
}

.depoimentos-clientes h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 2rem;
}

.depoimentos-clientes-info {
  display: flex;
  background-color: #151a2f;
  padding: 2rem;
}

.depoimentos-clientes-info-texto {
  display: flex;
  flex-direction: column;
  justify-content: center;

  width: 48%;
  color: #fff;
  text-align: center;
  padding: 2rem;
  margin-left: 3rem;
}

.depoimentos-clientes-info-texto-1 h3,
.depoimentos-clientes-info-texto-2 h3 {
  font-family: "Cormorant Garamond", serif;
  font-size: 3rem;
  margin-bottom: 2rem;
}

.depoimentos-clientes-info-texto-1 p {
  margin-bottom: 3rem;
}

.depoimentos-clientes-info-texto-1 p,
.depoimentos-clientes-info-texto-2 p {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.2rem;
  padding: 0 1rem;
}
</style>