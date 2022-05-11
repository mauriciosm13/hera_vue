<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">
      <img src="../assets/imagens/HeraRecorteTransparente.png" alt="Logo"
    /></a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="#sobre">Sobre Nós</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#ComoTrabalhamos">Como Trabalhamos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#testemunhos">Relatos</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Menu",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Alice&display=swap");

li {
  font-size: 1.2em;
  font-family: "Alice", serif;
}
</style>
