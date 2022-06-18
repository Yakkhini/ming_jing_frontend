<template>
  <img alt="Vue logo" src="./assets/logo.svg" />
  <BigTitle msg="明镜" />
</template>

<script>
import BigTitle from "./components/BigTitle.vue";

export default {
  name: "App",
  components: {
    BigTitle,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
