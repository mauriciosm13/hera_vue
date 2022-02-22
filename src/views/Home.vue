<template>
  <div class="home" style="margin: 0; padding: 0;">
    <Menu/>
    <Header/>
    <SobreNos/>
    <ComoTrabalhamos/>
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from "@/components/Menu.vue";
import Header from "@/components/Header.vue";
import SobreNos from "@/components/SobreNos.vue";
import ComoTrabalhamos from "@/components/ComoTrabalhamos.vue";

export default {
  name: "Home",
  components: {
    Menu,
    Header,
    SobreNos,
    ComoTrabalhamos
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