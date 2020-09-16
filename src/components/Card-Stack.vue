<template>
  <div class="container-fluid card-stack">
    <div class="container pb-1">
      <div class="row pt-2">
        <div class="col-md-4" v-for="project in projects" v-bind:key="project">
          <div class="card" id="step1">
            <a href="./errands.html" target="_blank">
              <div class="card-body">
                <h4 class="card-title">{{ project.title }}</h4>
                <p class="card-text">{{ project.summary }}</p>
              </div>
            </a>
          </div>
        </div>
      </div>
      <div class="row mt-1"></div>
      <div class="row mt-1 mb-5">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h4 class="card-title text-danger">Upcoming projects...</h4>
              <p class="card-text mb-0">
                <strong>Drag & Drop eShopping application</strong>
                <span class="text-danger">*</span>
              </p>
              <p class="card-text mb-0">
                <strong>betting application</strong>
                <span class="text-danger">*</span>
              </p>
              <p class="card-text mb-0">
                <strong>Driver request application</strong>
                <span class="text-danger">*</span>
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card-Stack",
  props: {},
  data: function () {
    return {
      projects: [
        {
          title: "Complete Errands App | JavaScript & Bootstrap",
          summary:
            "Do you need quick services of regular daily people to help do stuffs for you?",
          id: 1,
        },
        {
          title: "JavaScript",
          summary: "lorem ipsum",
          id: 2,
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card-stack {
  background: linear-gradient(145deg, rgb(173, 168, 173), rgb(236, 195, 195));
}

.card {
  cursor: pointer;
  border: none !important;
  border-radius: 10px;
  margin-top: 2rem;
  min-height: 200px;
  max-height: 250px;
}

.card:hover {
  background: rgb(252, 252, 252);
  background: linear-gradient(
    142deg,
    rgba(252, 252, 252, 1) 0%,
    rgba(242, 242, 242, 1) 83%,
    rgba(154, 231, 247, 1) 95%,
    rgba(0, 212, 255, 1) 100%
  );
}

a {
  color: #333;
}

a:hover {
  text-decoration: none;
}
</style>
