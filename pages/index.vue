<template>
  <div>
    <hero-banner/>
    <call-to-action/>
    <courses/>
     <courses/>
  </div>
</template>

<script>
import CallToAction from '../components/callToAction.vue'
import Courses from '../components/Courses.vue'
import heroBanner from '../components/heroBanner.vue'
  export default {
  components: { heroBanner, Courses, CallToAction },
    
  }
</script>

<style  scoped>

</style>