<template>
  <div class="container box">
    <div class="box" v-intro-step="2">
      <h1 class="mt-5 text-center title">
        Afolabi
        <span class="title2">Opakunle</span>
      </h1>
    </div>

    <p class="text-center p-3 lead text-white">
      A Front end designer and developer with vast knowledge of HTML,
      CSS,
      Bootstrap, JavaScript, Node, MongoDB,
      <span
        class="bolden"
      >VueJS</span> and other modern tools
    </p>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container.box {
  background-color: black !important;
}

.jumbotron .lead {
  /* max-width: 60%; */
  margin: 0 auto;
  text-shadow: 1px 3px 6px black;
  font-size: 1.5rem;
}

.container .title {
  padding-top: 4rem;
  letter-spacing: 3px;
  font-size: 4.5rem;
  margin: auto;
  font-family: "Baloo Bhai 2", cursive;
  color: white;
}

.container .title2 {
  font-size: 6rem;
}

.photo-box .container .lead {
  max-width: 700px;
  margin: auto;
  margin-bottom: 1.5rem;
}

span.bold {
  font-weight: 400;
}

@media only screen and (max-width: 600px) {
  .container .title {
    font-size: 3rem;
  }

  .container .title2 {
    font-size: 4rem;
  }
}
</style>
