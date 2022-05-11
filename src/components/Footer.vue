<template>
  <div class="footer">
    <div>
        <a href="https://wa.me/5511981748251" target="_blank"><img src="https://img.icons8.com/material-outlined/24/000000/whatsapp--v1.png"/></a>
        <a href="https://www.instagram.com/heraeventos_/" target="_blank"><img src="https://img.icons8.com/material-outlined/24/000000/instagram-new--v1.png"/></a>
      </div>
        {{ new Date().getFullYear() }} — Ω - <strong>omegatech</strong>
  </div>
</template>

<script>
export default {
  name: "Footer",
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
  height: 100vh;
}
.card {
  transition: box-shadow .3s;
  border-radius:20px;
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
}
</style>
