<template>
  <div class="menu">
    <nav class="links" style="--items: 5; position: fixed; width: 100%;">
      <a class="navbar-brand" href="#">
        <img
          src="../assets/imagens/HeraRecorteTransparente.png"
          alt="Logo"
        />
      </a>
      <a class="navbar-brand" href="#">Sobre Nós</a>
      <a class="navbar-brand" href="#">Como Trabalhamos</a>
      <a class="navbar-brand" href="#">Relatos</a>
      <a class="navbar-brand" href="#">Entre em Contato</a>
      <span class="line"></span>
    </nav>
  </div>
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
@import url('https://fonts.googleapis.com/css2?family=Alice&display=swap');

code {
  position: fixed;
  background: #fff1;
  font-family: 'Alice', serif;
  padding: 0.2em 0.4em;
}

.content {
  background-color: #fff;
  border-radius: 8px;
  box-sizing: border-box;
  color: #666;
  font-size: 1.6em;
  line-height: 1.4em;
  margin: 20px auto;
  margin-top: 80px;
  padding: 20px;
  width: 100%;
  max-width: 800px;
}
.content ul {
  margin: 0.5em 2em;
  padding: 0;
}
.navbar-brand {
  background-color: #f4f3f3;
  background-image: linear-gradient(to bottom, #0003, transparent);
  font-weight: 300;
}
/* Appearance */
.links {
  font-size: 1.2em;
  font-family: 'Alice', serif;
  background-color: #f4f3f3;
  background-image: linear-gradient(to bottom, #0003, transparent);
  border-bottom: 1px solid #945d41;
  box-shadow: 0 0 32px #0003;
}
.links > a {
  color: #0d5eaf;
  padding: 0.75em;
  text-align: center;
  text-decoration: none;
  transition: all 0.5s;
}
.links > a:hover {
  background: #ffffff06;
  color: #02101a;
}
.links > .line {
  background: #97784d;
  height: 1px;
  pointer-events: none;
}

/* The Magic */
#header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}
.links {
  display: grid;
  grid-template-columns: repeat(var(--items), 1fr);
  position: relative;
}
.links > .line {
  opacity: 0;
  transition: all 0.5s;
  position: absolute;
  bottom: 0;
  left: var(--left, calc(100% / var(--items) * (var(--index) - 1)));
  width: var(--width, calc(100% / var(--items)));
  --index: 0;
}
.links > a:hover ~ .line {
  opacity: 1;
}

.links > a:nth-of-type(1):hover ~ .line {
  --index: 1;
}
.links > a:nth-of-type(2):hover ~ .line {
  --index: 2;
}
.links > a:nth-of-type(3):hover ~ .line {
  --index: 3;
}
.links > a:nth-of-type(4):hover ~ .line {
  --index: 4;
}
.links > a:nth-of-type(5):hover ~ .line {
  --index: 5;
}
.links > a:nth-of-type(6):hover ~ .line {
  --index: 6;
}
.links > a:nth-of-type(7):hover ~ .line {
  --index: 7;
}
.links > a:nth-of-type(8):hover ~ .line {
  --index: 8;
}
.links > a:nth-of-type(9):hover ~ .line {
  --index: 9;
}
.links > a:nth-of-type(10):hover ~ .line {
  --index: 10;
}
.links > a:last-of-type:hover ~ .line {
  --index: var(--items);
}
</style>
