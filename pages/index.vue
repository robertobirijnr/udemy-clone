<template>
  <div>
    <hero-banner/>
    <courses/>
  </div>
</template>

<script>
import Courses from '../components/Courses.vue'
import heroBanner from '../components/heroBanner.vue'
  export default {
  components: { heroBanner, Courses },
    
  }
</script>

<style  scoped>

</style>