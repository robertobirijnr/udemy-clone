<template>
  <div>
    <hero-banner />
    <call-to-action />
    <courses />
    <courses />
    <main-banner />
    <courses />
  </div>
</template>

<script>
import CallToAction from '../components/callToAction.vue'
import Courses from '../components/Courses.vue'
import heroBanner from '../components/heroBanner.vue'
import MainBanner from '../components/mainBanner.vue'
  export default {
  components: { heroBanner, Courses, CallToAction,MainBanner },
    
  }
</script>

<style  scoped>

</style>