<template>
  <NavBar/>
  <About/>
  <Resume/>
  <Footer/>
</template>
<script>
import NavBar from '../components/NavBar.vue';
import Footer from '../components/Footer.vue';
import About from '../components/About.vue';
import Resume from '../components/Resume.vue'
export default {
  components: {
    NavBar,
    Footer,
    About,
    Resume
  }
}
  </script>
  <style scoped>
    
  </style>
