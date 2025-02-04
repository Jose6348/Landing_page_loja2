<template>
  <div class="barra-navegacao">
    <nav class="links-barra-navegacao">
      <a class="cor-barra-navegacao" href="/#cabecalho">Início</a>
      <a class="cor-barra-navegacao" href="/#depoimentos-clientes">Sobre</a>
      <a class="cor-barra-navegacao" href="/#primeira-secao">Cardápio</a>
      <a class="cor-barra-navegacao" href="/#nossas-filiais">Blog</a>
      <a class="cor-barra-navegacao" href="/#segunda-secao">Loja</a>
      <a class="cor-barra-navegacao" href="/#contato">Contato</a>
    </nav>
    <div class="logo-barra-navegacao redes-sociais-barra-navegacao">
      <img src="../../public/img/LogoWhite.png" alt="" width="35" height="40" />
      <p>CoffeeCup</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "BarraNavegacao",
};
</script>

<style >
.barra-navegacao {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8rem 1.5rem 6rem 4rem;
  font-family: "Roboto", sans-serif;
  font-size: 1.6rem;
}

.links-barra-navegacao a {
  margin-right: 4rem;
  text-decoration: none;
  color: #1d2440;
  position: relative;
}

.links-barra-navegacao a::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 4px;
  bottom: 0;
  left: 0;
  background-color: #FF4900;
  visibility: hidden;
  -webkit-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transition: all 0.3s ease-in-out 0s;
  transition: all 0.3s ease-in-out 0s;
}

.links-barra-navegacao a:hover:before {
  visibility: visible;
  -webkit-transform: scaleX(1);
  transform: scaleX(1);
}

.logo-barra-navegacao {
  display: flex;
  width: 100px;
  align-items: center;
  margin-right: 11%;
}

.logo-barra-navegacao p {
  margin: 0rem 5rem 0rem 0.5rem;
  color: #fff;
}
</style>