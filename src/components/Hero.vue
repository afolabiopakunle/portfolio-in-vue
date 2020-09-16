<template>
  <div class="container box">
    <div class="box" id="step2">
      <h1 class="display-3 mt-5 text-center title h2s">
        Afolabi
        <span class="display-1">Opakunle</span>
      </h1>
    </div>

    <p class="text-center p-3 lead text-white">
      A Front end designer and developer with vast knowledge of HTML,
      CSS,
      Bootstrap, JavaScript, Node, MongoDB,
      <span class="bolden">VueJS</span> and other modern tools
    </p>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.myLogo {
  width: 40px;
  margin-right: 30px;
}

.button_slide {
  color: white !important;
  display: inline-block;
  cursor: pointer;
  box-shadow: inset 0 0 0 0 #007bff;
  transition: box-shadow ease-in-out 0.6s;
}

.slide_right:hover {
  box-shadow: inset 400px 0 0 0 #007bff;
  color: #eee !important;
}

.nav-item {
  padding-right: 40px;
  font-weight: 600;
}
</style>
