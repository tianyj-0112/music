<template>
  <div id="app">
    <router-view />
    <login-register />
  </div>
</template>
<script>
import LoginRegister from "./views/LoginRegister.vue";
export default {
  components: {
    LoginRegister,
  },
};
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
