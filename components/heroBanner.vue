<template>
  <div class="container-fluid banner-bg d-flex justify-content-center align-items-center">
    <div class="row">
      <div class="col">
        <h1 class="display-3">Explore your creativity.</h1>
        <br />
        <h3>Join CodeBooth to watch, play, learn, make, and discover.</h3>
        <button class="btn mt-4 btn-ml btn-outline-info btn-lg">
          Get Started Now
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
.banner-bg {
  background: #ffaf3c;
  height: 400px;
  color: #002333;
}

.btn-outline-info {
  color: #002333 !important;
  border-color: #002333 !important;
}

.btn-outline-info:hover {
  color: #fff !important;
  background: #002333!important;
}

.btn-ml {
  margin-left: 30%;
}

@media (max-width: 575px) {
  .row {
    padding-top: 100px !important;
  }

  .display-3 {
    font-size: 50px !important;
    text-align: center !important;
  }

  h3 {
    font-size: 20px !important;
    text-align: center !important;
  }
  .banner-bg {
    background: #ffaf3c;
    height: 550px;
    color: #002333;
  }
  .btn-ml {
  margin-left: 20%;
}
}
</style>