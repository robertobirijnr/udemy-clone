<template>
  <div class="container">
    <div class="mt-5 d-flex justify-content-center">
      <span>
        <h1 class="pl-5">Find What Fascinates You</h1>
        <p>
          Choose from 130,000 online video courses with new additions published
          every month
        </p>
      </span>
    </div>
    <ul class="d-flex">
      <li><nuxt-link to="/">All Courses</nuxt-link></li>
      <li><nuxt-link to="/">UI/UX Design</nuxt-link></li>
      <li><nuxt-link to="/">Graphics Design</nuxt-link></li>
      <li><nuxt-link to="/">Frontend</nuxt-link></li>
      <li><nuxt-link to="/">Backend</nuxt-link></li>
      <li><nuxt-link to="/">Fullstack</nuxt-link></li>
      <li><nuxt-link to="/">DevOps</nuxt-link></li>
      <li><nuxt-link to="/">Business</nuxt-link></li>
      <li><nuxt-link to="/">Blockchain</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
h1 {
  font-weight: 700;
}

ul {
  display: flex;
  list-style: none;
  justify-content: space-evenly;
}

li a{
    color: #002333;
    text-decoration: none;
    font-weight: bold;
}
</style>