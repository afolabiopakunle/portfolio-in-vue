<template>
  <div id="app">
    <AppHeader msg="Welcome Afolabi VueJS" />
    <Hero />
    <div class="container-fluid border shadow-sm"></div>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import Hero from "./components/Hero";

export default {
  name: "App",
  components: {
    AppHeader,
    Hero,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Muli&display=swap");
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: "Muli", sans-serif;
  user-select: none;
  background: black;
  user-select: none;
  -webkit-user-drag: none;
}
</style>
