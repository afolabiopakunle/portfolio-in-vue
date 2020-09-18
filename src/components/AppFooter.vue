<template>
  <div class="container-fluid bg-white p-0">
    <div class="container">
      <a
        href="https://martinasapartments.com/hardstorage/2020/08/Afolabi-O.-Opakunle-Front-End.pdf"
        target="_blank"
      >
        <h1 class="text-success text-center p-5">Click To Download Resume</h1>
      </a>
      <div class="row pl-5 pt-2">
        <div class="col-md-6">
          <a href="mailto:opakunleafolabi@gmail.com" id="step4">
            <img src="../assets/afolabi logo.png" width="30" alt="logo" />
            <span class="font-weight-bold">opakunleafolabi@gmail.com</span> just
            <span class="bg-primary p-1 rounded text-white">Hire me!</span>
          </a>
          <p>Delivering clear-cut Frontend user interfaces since 2017.</p>
          <div class="box-in">
            <div class="spin-container">
              <div class="shape">
                <div class="bd"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row">
            <div class="col-md-4">
              <h6 class="text-danger">Mentors</h6>
              <a href="https://github.com/ezra-obiwale" target="_blank" rel="noopener noreferrer">
                <p class="footnote">Ezra Obiwale</p>
              </a>
              <a href="https://github.com/bradtraversy" target="_blank" rel="noopener noreferrer">
                <p class="footnote">Brad Traversy</p>
              </a>
              <a href="https://github.com/designcourse" target="_blank" rel="noopener noreferrer">
                <p class="footnote">Gary Simon</p>
              </a>
              <a
                href="https://www.youtube.com/c/ColtSteeleCode/featured"
                target="_blank"
                rel="noopener noreferrer"
              >
                <p class="footnote">Colt Steele</p>
              </a>
            </div>
            <div class="col-md-4">
              <h6 class="text-danger">Students</h6>
              <p class="footnote">Peace Moyosore</p>
              <p class="footnote">Emeka Ohaeri</p>
            </div>
            <div class="col-md-4">
              <h6 class="text-danger">Recommended Sites</h6>
              <a href="https://www.freecodecamp.org/" target="_blank" rel="noopener noreferrer">
                <p class="footnote">freeCodeCamp.org</p>
              </a>
              <a href="https://www.pluralsight.com/" target="_blank" rel="noopener noreferrer">
                <p class="footnote">Pluralsight.com</p>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box-in {
  width: 200px;
  height: 200px;
  border: 1px dashed rgba(255, 255, 255, 0.4);
  position: relative;
}

.spin-container {
  width: 100%;
  height: 100%;
  animation: spin 3s linear infinite;
  position: relative;
}

.shape {
  width: 100%;
  height: 100%;
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
  transition: border-radius 1s ease-out;
  border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
  animation: morph 4s ease-in-out infinite both alternate;
  position: absolute;
  overflow: hidden;
  z-index: 5;
}

.footnote {
  color: #666666;
  margin-bottom: 2px;
}

.bd {
  width: 142%;
  height: 142%;
  position: absolute;
  left: -21%;
  top: -21%;
  background-size: 100%;
  background-position: center center;
  display: flex;
  color: #003;
  font-size: 5vw;
  font-weight: bold;
  align-items: center;
  justify-content: center;
  text-align: center;
  text-transform: uppercase;
  animation: spin 3s linear infinite reverse;
  opacity: 1;
  z-index: 2;
  background: url(../assets/afolabi.png);
  background-size: cover;
  background-repeat: none;
}

@keyframes morph {
  0% {
    border-radius: 40% 60% 60% 40% / 60% 30% 70% 40%;
  }

  100% {
    border-radius: 40% 60%;
  }
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}
</style>
