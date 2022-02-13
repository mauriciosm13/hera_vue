<template>
  <div class="home" style="margin: 0; padding: 0;">
    <Menu/>
    <Header/>
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from "@/components/Menu.vue";
import Header from "@/components/Header.vue";

export default {
  name: "Home",
  components: {
    Menu,
    Header
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