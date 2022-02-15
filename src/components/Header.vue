<template>
  <div class="header">
    <img alt="Header" src="../assets/imagens/Header.png">
    
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
img
{
   margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
