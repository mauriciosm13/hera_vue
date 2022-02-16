<template>
  <div class="home" style="margin: 0; padding: 0;">
    <Menu/>
    <Header/>
     <SobreNos/>
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from "@/components/Menu.vue";
import Header from "@/components/Header.vue";
import SobreNos from "@/components/SobreNos.vue";

export default {
  name: "Home",
  components: {
    Menu,
    Header,
    SobreNos
  },
  data() {
    return {
    };
  },
  methods: {
  },
};
</script>
<style>
html{
  margin:0;
  padding: 0;
}
</style>