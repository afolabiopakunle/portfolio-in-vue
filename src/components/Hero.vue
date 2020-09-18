<template>
  <div class="container box">
    <div class="box" id="step2">
      <h1 class="display-3 mt-5 text-center title h2s">
        Afolabi
        <span class>Opakunle</span>
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
  max-width: 60%;
  margin: 0 auto;
  text-shadow: 1px 3px 6px black;
  font-size: 1.5rem;
}

.container .title {
  padding-top: 4rem;
  letter-spacing: 3px;
  margin: auto;
  font-family: "Baloo Bhai 2", cursive;
  color: white;
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
  body {
    background-color: lightblue;
  }
}
</style>
