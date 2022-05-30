<template>
  <header>
    <span class="texto-header">home</span>
    <span class="separador"> </span>
    <span class="texto-header"> jogadores</span>
    <span class="separador"> </span>
    <span class="texto-header">Times</span>
  </header>
  <main>main</main>
  <footer>rodapé</footer>
</template>

<style>
@import "./assets/base.css";

#app {
  max-width: 1920px;
  margin: 0 auto;
  padding: 2rem;
  background-color: aqua;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

header,
footer {
  background-color: blue;
  height: 15%;
  font-size: 1.3rem;
  color: #fff;
}

main {
  min-height: 70%;
}

header span {
  padding: 0 10px;
}
</style>
