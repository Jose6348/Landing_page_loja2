<template>
  <div class="horario-funcionamento">
    <h2>Estamos Abertos</h2>
    <div class="horario-funcionamento-semana">
      <p>Segunda a Sexta</p>
      <p>08:00 - 23:30</p>
    </div>
    <div class="horario-funcionamento-fim-semana">
      <p>Sábado e Domingo</p>
      <p>09:00 - 22:30</p>
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
}

.horario-funcionamento h2 {
  font-family: "Cormorant Garamond", serif;
  font-size: 5rem;
  color: #1d2440;
  text-align: center;
  margin-bottom: 2rem;
}

.horario-funcionamento-semana,
.horario-funcionamento-fim-semana {
  width: 35%;
  padding: 4rem;
  margin: 2rem;
  color: #FFF;
  font-size: 2rem;
  text-align: center;
  font-family: "Noto Sans", sans-serif;
  background-color: #233e6a;
  box-shadow: 5px 5px 10px 0px rgb(104, 102, 102);
}
</style>