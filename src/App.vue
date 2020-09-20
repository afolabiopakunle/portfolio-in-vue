<template>
  <div id="app">
    <AppHeader @startIntro="startIntro" />
    <Hero />
    <div class="container-fluid border shadow-sm"></div>
    <AppCards :projects="projects" />
    <div class="container-fluid border shadow-sm"></div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader";
import Hero from "./components/Hero";
import AppCards from "./components/AppCards";
import AppFooter from "./components/AppFooter";
export default {
  name: "App",
  props: [],
  components: {
    AppHeader,
    Hero,
    AppCards,
    AppFooter,
  },
  data() {
    return {
      projects: [
        {
          title: "Complete Errands App | JavaScript & Bootstrap",
          summary:
            "Do you need quick services of regular daily people to help do stuffs for you?",
          id: 1,
          url: "./errands.html",
        },
        {
          title: "Playstore App Landing Page",
          summary:
            "Landing page design has evolved over a short period of time. This design is modern and ageless.",
          id: 2,
        },
        {
          title: "Apartments Booking Website",
          summary:
            "This website is targeted at converting visitors to book an apartment with Martinas. ",
          id: 3,
          url: "https://perfecthavensapartments.com",
        },
        {
          title: "Sports Website Project",
          summary:
            "Adrenalined filled sports webpage with trendy color selection and user-friendly backend cms functionalities.",
          id: 4,
          url: "https://sportsglobaltv.com",
        },
        {
          title: "JavaScript Shopping List",
          summary:
            "Search enabled shopping list app, constructed with the use of plain JavaScript with commented jQuery version included. ",
          id: 5,
        },
        {
          title: "My Designs",
          summary:
            "Page contains screenshots of previous designs and concepts I delivered using Figma and AdobeXD in some projects",
          id: 6,
        },
      ],
    };
  },
  methods: {
    startIntro() {
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
  position: relative;
  min-width: 320px;
}
</style>
