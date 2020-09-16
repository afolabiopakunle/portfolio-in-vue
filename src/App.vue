<template>
  <div id="app">
    <AppHeader msg="Welcome Afolabi VueJS" />
    <Hero />
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
