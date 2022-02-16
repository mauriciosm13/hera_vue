<template>
  <div class="sobre">
    <div class="container">
      <div class="card">
        <div class="face face1" style="width: 100%">
          <div class="content">
            <h3>Quem somos nós?</h3>
          </div>
        </div>
        <div class="face face2" style="width: 100%">
          <div class="content">
            <p>
              Somos a Hera Eventos, uma empresa especializada em eventos únicos
              e com a personalidade dos nossos clientes. As nossas palavras
              chaves são cuidado e presença. A Hera nasceu do sonho de ser uma
              empresa de assessoria que trabalha muito próxima ao seu cliente
              entendendo as necessidades, os sonhos, o que é importante para
              eles e o que não é.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SobreNos",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Alice&display=swap");
body {
  margin: 0;
  padding: 0;
  min-height: 100vh;
  background: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Alice", serif;
}

.container {
  width: 100%;
  position: relative;
  display: flex;
  justify-content: space-between;
}

.container .card {
  position: relative;
  cursor: pointer;
}

.container .card .face {
  width: 80%;
  height: 200px;
  transition: 0.8s;
}

.container .card .face.face1 {
  position: relative;
  background: #0d5eaf;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1;
  transform: translateY(100px);
}

.container .card:hover .face.face1 {
  background: #97784d;
  transform: translateY(0);
}

.container .card .face.face1 .content {
  opacity: 0.2;
  transition: 0.5s;
}

.container .card:hover .face.face1 .content {
  opacity: 1;
}

.container .card .face.face1 .content img {
  max-width: 100%;
}

.container .card .face.face1 .content h3 {
  margin: 10px 0 0;
  padding: 0;
  color: #fff;
  text-align: center;
  font-size: 1.5em;
  font-family: "Alice", serif;
}

.container .card .face.face2 {
  position: relative;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  box-sizing: border-box;
  transform: translateY(-100px);
}

.container .card:hover .face.face2 {
  transform: translateY(0);
}

.container .card .face.face2 .content p {
  margin: 0;
  padding: 0;
  font-family: "Alice", serif;
}

.container .card .face.face2 .content a {
  margin: 15px 0 0;
  display: inline-block;
  text-decoration: none;
  font-weight: 900;
  color: #333;
  padding: 5px;
  border: 1px solid #333;
}

.container .card .face.face2 .content a:hover {
  background: #333;
  color: #fff;
}
</style>
