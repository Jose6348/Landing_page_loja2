<template>
  <div id="depoimentos-clientes" class="depoimentos-clientes">
    <h2>Depoimentos de Clientes</h2>
    <div class="carousel">
      <div class="carousel-item" v-for="(depoimento, index) in depoimentos" :key="index">
        <div class="depoimento-card">
          <img :src="depoimento.imagem" :alt="`Depoimento de ${depoimento.nome}`" class="cliente-foto" />
          <div class="depoimento-texto">
            <h3>{{ depoimento.nome }}</h3>
            <p>{{ depoimento.texto }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DepoimentosClientes",
  data() {
    return {
      depoimentos: [
        {
          nome: "João Pedro",
          texto: "Adoro este produto! Facilitou muito minha vida e me ajudou a economizar tempo. Recomendo para todos!",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        {
          nome: "Elisa Thomaz",
          texto: "Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        {
          nome: "Elisa Thomaz",
          texto: "Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        {
          nome: "Elisa Thomaz",
          texto: "Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        {
          nome: "Elisa Thomaz",
          texto: "Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        {
          nome: "Elisa Thomaz",
          texto: "Desde que comecei a usar este serviço, minha produtividade aumentou significativamente. A interface é intuitiva e o suporte é excelente.",
          imagem: "https://github.com/Jose6348/Images_Projects/blob/main/Cafe_page/pexels-ann-h-45017-11022644.jpg?raw=true"
        },
        // Adicione mais depoimentos aqui conforme necessário
      ]
    };
  }
};
</script>

<style scoped>
.depoimentos-clientes {
  padding: 4rem;
  text-align: center;
}

.depoimentos-clientes h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 4rem;
  color: #1d2440;
  margin-bottom: 2rem;
}

.carousel {
  display: flex;
  overflow-x: auto;
  gap: 2rem;
  padding: 2rem 0;
}

.carousel-item {
  flex: 0 0 auto;
}

.depoimento-card {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  padding: 2rem;
  width: 300px;
  text-align: center;
  margin: 0 auto;
}

.cliente-foto {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

.depoimento-texto h3 {
  font-family: "Cormorant Garamond", serif;
  font-size: 2rem;
  color: #1d2440;
  margin-bottom: 1rem;
}

.depoimento-texto p {
  font-family: "Noto Sans", sans-serif;
  font-size: 1rem;
  color: #333;
}
</style>