<template>
    <main>
    <NavBar/>
    <Projects/>
    <Footer/>
    </main>
  </template>
  <script>
  import NavBar from '../components/NavBar.vue';
  import Footer from '../components/Footer.vue';
  import Projects from '../components/Projects.vue'
  export default {
    components: {
      NavBar,
      Footer,
      Projects
    }
  }
    </script>
    <style scoped>
      
    </style>