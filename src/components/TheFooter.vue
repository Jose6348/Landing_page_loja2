<template>
  <div id="contato" class="rodape">
    <div class="logo-rodape">
      <img src="../../public/img/LogoWhite.png" alt="" width="65" height="70" />
      <p>CoffeeCup</p>
    </div>
    <div class="informacao-rodape">
      <ul>
        <li class="principal">Informações.</li>
        <li>Sobre nós</li>
        <li>Filiais</li>
        <li>Cardápio</li>
        <li>Contato</li>
        <li>Mapa</li>
      </ul>
    </div>
    <div class="contato-rodape">
      <ul>
        <li class="principal">Entre em Contato.</li>
        <li>Suporte</li>
        <li>seu_id@gmail.com</li>
      </ul>
    </div>
  </div>

  <div class="navbar-e-redes-sociais">
    <Navbar class="navbar-rodape" />
    <div class="redes-sociais">
      <i class="bi bi-facebook"></i>
      <i class="bi bi-instagram"></i>
      <i class="bi bi-twitter"></i>
      <i class="bi bi-youtube"></i>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  name: "TheFooter",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.rodape {
  display: flex;
  background-color: #1d2440;
  padding: 6rem 0 2rem 6rem;
}

.logo-rodape {
  display: flex;
  width: 60%;
}

.logo-rodape p {
  font-family: "Noto Sans", sans-serif;
  font-size: 3rem;
  color: #fff;
  margin-left: 1rem;
}

.informacao-rodape,
.contato-rodape {
  width: 20%;
  font-family: "Roboto", sans-serif;
  color: #fff;
  font-size: 1rem;
}

.informacao-rodape li,
.contato-rodape li {
  list-style: none;
  line-height: 2.3rem;
  font-size: 1.4rem;
  cursor: pointer;
}

.principal {
  font-size: 2rem !important;
  padding-bottom: 2rem;
  font-weight: bold;
}

.navbar-rodape {
  padding: 4rem 0 3rem 6rem;
  background-color: #1d2440;
}

:deep(.cor-barra-navegacao) {
  color: #fff !important;
  font-size: 1.5rem;
}

:deep(.cor-barra-navegacao):hover {
  color: #ff540e !important;
}

:deep(.redes-sociais-barra-navegacao) {
  display: none;
}

.navbar-e-redes-sociais {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #1d2440;
}

.redes-sociais {
  width: 300px;
  height: 10px;
}

.redes-sociais i {
  color: #ff540e;
  padding: 0 1rem;
  font-size: 1.6rem;
  cursor: pointer;
}

.redes-sociais i:hover {
  color: #FFF;
}
</style>