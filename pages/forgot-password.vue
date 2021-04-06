<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg col-md-6 d-flex justify-content-center form-container">
        <div class="col-lg-4 col-md-6 col-sm-9 col-xs-12 form-box text-center">
          <div class="heading pt-5 pb-3">
              <img src="../assets/password.png" height="100px" alt="">
            <h4>Forgot Password</h4>
            <p>Enter your email and we will send you a link to reset your password</p>
          </div>
          <form>
            <div class="form-input">
              <span><i class="fa fa-envelope"></i></span>
              <input type="email" placeholder="Email Address" required />
            </div>

            <button class="btn btn-warning btn-block text-white">Submit</button>
          </form>
          <div class="d-flex justify-content-between pt-3">
            <nuxt-link to="/"
              ><span id="home"
                ><i class="fa fa-home"></i> Back To Home</span
              ></nuxt-link
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "form",
};
</script>

<style  scoped>
.container-fluid {
  background: #002333;
  height: 100vh;
}



p {
  color: #fff;
}

.text-white {
  color: #002333 !important;
  font-weight: bold;
  text-transform: uppercase;
}

.form-box {
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 70vh;
}

.form-box h4 {
  font-weight: bold;
  color: #fff;
}

form {
  border-radius: 10px;
}

.form-box .form-input {
  position: relative;
}

.form-box .form-input input {
  width: 100%;
  height: 40px;
  margin-bottom: 20px;
  border: none;
  border-radius: 5px;
  outline: none;
  background: #e8f0fe;
  padding-left: 45px;
}

.form-box .form-input span {
  position: absolute;
  top: 8px;
  padding-left: 20px;
  color: #777;
}

#home {
  color: #fff;
}

a {
  text-decoration: none;
}

.btn:focus {
  outline: 0;
  border: none;
}
</style>