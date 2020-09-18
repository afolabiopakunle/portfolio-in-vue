<template>
  <header>
    <nav id="navbar" class="navbar navbar-expand bg-warning navbar-dark fixed-top">
      <div class="container">
        <a class="navbar-brand text-dark" href="#">
          <img src="../assets/afolabi logo.png" alt="Logo" class="myLogo" />
          <button class="btn btn-primary">Show Me Around</button>
        </a>
        <ul class="navbar-nav" id="step3">
          <li class="nav-item">
            <a
              class="nav-link rounded button_slide slide_right"
              target="_blank"
              title="Github"
              href="https://github.com/afolabiopakunle"
            >GitHub</a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link rounded button_slide slide_right"
              title="Twitter"
              target="_blank"
              href="https://twitter.com/AfolabiOpa"
            >Twitter</a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link rounded ml-4 button_slide slide_right"
              target="_blank"
              href="https://www.linkedin.com/in/afolabi-opakunle-836048197/"
            >LinkedIn</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
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
