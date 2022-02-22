<template>
  <div class="sobre">
    <center><div class="card text-center" style="width: 65%">
      <center><img
        class="card-img-top"
        src="../assets/imagens/sobrenos.png"
        alt="Card image cap"
      /></center>
      <div class="card-body">
        <h2>Sobre Nós </h2>
        <p class="card-text">
          Somos a Hera Eventos, uma empresa especializada em eventos únicos e
          com a personalidade dos nossos clientes. As nossas palavras chaves são
          cuidado e presença. Sou a Natália, assessora da Hera, tenho 29 anos,
          estou há mais de 5 anos no mercado de eventos e tenho mais de 310
          sonhos realizados. A Hera nasceu do sonho de ser uma empresa de
          assessoria que trabalha muito próxima ao seu cliente entendendo as
          necessidades, os sonhos, o que é importante para eles e o que não é.
        </p>
      </div>
    </div></center>
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
.sobre{
  background-color: #f4f6f7;
}
.card {
  transition: box-shadow .3s;
  border-radius:10px;
  border: 1px solid #ccc;
  background: #fff;
  box-shadow: 0 0 11px rgba(206, 204, 204, 0.2); 
  font-family: "Alice", serif;
}
.card:hover {
  box-shadow: 0 0 11px #00000042; 
}
.card-img-top {
  width: 100%;
  height: auto;
}
</style>
