<template>
  <div class="header-container">
    <header class="the-header">
      <TheSideNavToggle @toggle="$emit('sidenavToggle')" />
      <div class="logo">
        <nuxt-link to="/">CodeBooth</nuxt-link>
      </div>
      <div class="search_bar">
        <input type="search" placeholder="What do you want to learn today?" />
      </div>
      <div class="spacer"></div>
      <div class="navigation-items">
        <ul class="nav-list">
          <li class="nav-item pt-2">
            <nuxt-link to="/posts">Courses</nuxt-link>
          </li>
          <li class="nav-item pt-2">
            <nuxt-link to="/about">Categories</nuxt-link>
          </li>
          <li class="nav-item pt-2">
            <nuxt-link to="/admin">Team Plans</nuxt-link>
          </li>
          <li class="nav-item btn btn-outline-info">
            <nuxt-link class="text-white" to="/signup">Sign Up</nuxt-link>
          </li>
          <li class="nav-item btn btn-outline-info">
            <nuxt-link class="text-white" to="/signin">Sign In</nuxt-link>
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
import TheSideNavToggle from "@/components/Navigation/TheSideNavToggle";

export default {
  name: "TheHeader",
  components: {
    TheSideNavToggle,
  },
};
</script>


<style scoped>
.header-container {
  height: 60px;
}

.the-header {
  width: 100%;
  position: fixed;
  height: 70px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #002333;
  z-index: 100;
  box-sizing: border-box;
  box-shadow: 0 4px 2px -2px gray;
  padding: 0 20px;
}

.logo {
  margin: 0 10px;
  font-size: 1.3rem;
  font-family: "Merriweather", serif;
}

.logo a {
  text-decoration: none;
  color: #fff;
}

.spacer {
  flex: 1;
}

.navigation-items {
  display: none;
}

@media (min-width: 768px) {
  .navigation-items{
    display: block;
  }
}

@media (max-width:575px){
  .search_bar input{
    display: none;
  }
}

.search_bar{
    display: none;
  }

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

.nav-item {
  margin: 0 10px;
}

.nav-item a {
  text-decoration: none;
  color: #fff;
}

.text-white {
  color: #ffffff !important;
}

.nav-item a:hover,
.nav-item a:active,
.nav-item a.nuxt-link-active {
  color: #86bdc5;
}

/* search bar */
 .search_bar{
    display: flex;
    margin: auto;
    height: 35px;
    line-height: 35px;
}

.search_bar input {
  width: 600px;
  height: 35px;
  border: none;
  outline: none;
  padding: 0 10px;
  font-size: 16px;
  border-radius: 13px;
  margin-left: 20px;
}

input,
input::-webkit-input-placeholder {
    font-size: 14px;
    color: #002333;
    padding-left: 5px;
}


.search_bar span:hover::after{
    width: 100%;
}


</style>
