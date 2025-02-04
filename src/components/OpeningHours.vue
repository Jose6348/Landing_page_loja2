<template>
  <div class="horario-funcionamento">
    <h2>Estamos Abertos</h2>
    <div class="horario-container">
      <div class="horario-card">
        <i class="fas fa-business-time"></i>
        <div class="horario-detalhes">
          <p class="dias">Segunda a Sexta</p>
          <p class="horario">08:00 - 23:30</p>
        </div>
      </div>
      <div class="horario-card">
        <i class="fas fa-calendar-alt"></i>
        <div class="horario-detalhes">
          <p class="dias">Sábado e Domingo</p>
          <p class="horario">09:00 - 22:30</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HorarioFuncionamento",
};
</script>

<style scoped>
.horario-funcionamento {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 1.5rem 0 3rem 0;
  padding: 2rem;
  background-color: #f5f5f5;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.horario-funcionamento h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 3rem; /* Reduzido para um tamanho mais apropriado */
  color: #1d2440;
  text-align: center;
  margin-bottom: 2rem;
}

.horario-container {
  display: flex;
  justify-content: center;
  width: 100%;
  gap: 2rem;
}

.horario-card {
  display: flex;
  align-items: center;
  width: 45%;
  padding: 2rem;
  background-color: #233e6a;
  color: #FFF;
  border-radius: 8px;
  box-shadow: 5px 5px 10px 0px rgba(104, 102, 102, 0.5);
  transition: transform 0.3s ease-in-out;
}

.horario-card:hover {
  transform: scale(1.05);
}

.horario-card i {
  font-size: 3rem;
  margin-right: 1.5rem;
}

.horario-detalhes {
  text-align: left;
}

.horario-detalhes .dias {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.5rem;
  margin: 0;
}

.horario-detalhes .horario {
  font-family: "Noto Sans", sans-serif;
  font-size: 1.2rem;
  margin: 0.5rem 0 0;
  opacity: 0.8;
}
</style>