<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg col-md-6 d-flex justify-content-center form-container">
        <div class="col-lg-4 col-md-6 col-sm-9 col-xs-12 form-box text-center">
          <div class="heading pt-5 pb-3">
            <h4>Sign in to CodeBooth</h4>
          </div>

          <div class="social-media pb-5">
            <img src="~/assets/google.png" height="50px" alt="" />
            <img src="~/assets/email.png" height="50px" alt="" />
            <img src="~/assets/linkedin.png" height="50px" alt="" />
          </div>
          <p>Or sign in with your email and password</p>
          <form>
            

            <div class="form-input">
              <span><i class="fa fa-envelope"></i></span>
              <input type="email" placeholder="Email Address" required />
            </div>
            <div class="form-input">
              <span><i class="fa fa-lock"></i></span>
              <input type="password" placeholder="Password" required />
            </div>
            <button class="btn btn-warning btn-block text-white">
              Sign In
            </button>
          </form>
          <div class="d-flex justify-content-between pt-3">
            <nuxt-link to="/"
              ><span id="home"
                ><i class="fa fa-home"></i> Back To Home</span
              ></nuxt-link
            >
            <p>
              Don't have an Account ? <nuxt-link to="/signup">sign up</nuxt-link>
            </p>
          </div>
         <nuxt-link to="/"> <p class="text-warning">Forgot your password ?</p></nuxt-link>
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

.btn:focus{
    outline: 0;
    border: none;
}
</style>