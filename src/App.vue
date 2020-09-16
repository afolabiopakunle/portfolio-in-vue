<template>
  <div id="app">
    <AppHeader @startIntro="startIntro" />
    <Hero />
    <div class="container-fluid border shadow-sm"></div>
    <Card-Stack />
    <div class="container-fluid border shadow-sm"></div>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import Hero from "./components/Hero";
import CardStack from "./components/Card-Stack";
export default {
  name: "App",
  props: [],
  components: {
    AppHeader,
    Hero,
    CardStack,
  },
  methods: {
    startIntro: function () {
      alert("Hi");
    },
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
