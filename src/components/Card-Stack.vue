<template>
  <div class="container-fluid card-stack">
    <div class="container pb-1">
      <div class="row pt-2">
        <div class="col-md-4">
          <div class="card" id="step1">
            <a href="./errands.html" target="_blank">
              <div class="card-body">
                <h4 class="card-title">Complete Errands App | JavaScript & Bootstrap</h4>
                <p class="card-text">
                  Do you need quick services of regular daily people to help do
                  stuffs for you?
                </p>
              </div>
            </a>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card">
            <a href="./gofer.html" target="_blank">
              <div class="card-body">
                <h4 class="card-title">Playstore App Landing Page</h4>
                <p class="card-text">
                  Landing page design has evolved over a short period of time.
                  This design is modern and ageless.
                </p>
              </div>
            </a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <a href="https://www.martinasapartments.com" target="_blank">
              <div class="card-body">
                <h4 class="card-title">Hotel Booking Website</h4>
                <p class="card-text">
                  This website is targeted at converting visitors to book an
                  apartment with Martinas.
                </p>
              </div>
            </a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <a href="https://www.sportsglobaltv.com" target="_blank">
              <div class="card-body">
                <h4 class="card-title">Sports Website Project</h4>
                <p class="card-text">
                  Adrenalined filled sports webpage with trendy color selection
                  and user-friendly backend cms functionalities.
                </p>
              </div>
            </a>
          </div>
        </div>
        <div class="col-md-4">
          <a href="./todo.html" target="_blank">
            <div class="card">
              <div class="card-body">
                <h4 class="card-title">JavaScript Shopping List</h4>
                <p class="card-text">
                  Search enabled shopping list app, constructed with the use of
                  plain JavaScript with commented jQuery version included.
                </p>
              </div>
            </div>
          </a>
        </div>
        <div class="col-md-4">
          <a href="https://dribbble.com/afolabiopakunle" target="_blank">
            <div class="card">
              <div class="card-body">
                <h4 class="card-title">My Designs</h4>
                <p class="card-text">
                  Page contains screenshots of previous designs and concepts I
                  delivered using Figma and AdobeXD in some projects
                </p>
              </div>
            </div>
          </a>
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
