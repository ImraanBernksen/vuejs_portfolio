<template>
    <NavBar/>
    <Testimonials/>
    <Footer/>
  </template>
  <script>
  import NavBar from '../components/NavBar.vue';
  import Footer from '../components/Footer.vue';
  import Testimonials from '../components/Testimonials.vue'
  export default {
    components: {
      NavBar,
      Footer,
      Testimonials
    }
  }
    </script>
    <style scoped>
      
    </style>