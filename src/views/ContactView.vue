<template>
    <NavBar/>
    <ContactForm/>
    <Footer/>
  </template>
  <script>
  import NavBar from '../components/NavBar.vue';
  import Footer from '../components/Footer.vue';
  import ContactForm from '../components/ContactForm.vue'
  export default {
    components: {
      NavBar,
      Footer,
      ContactForm
    }
  }
    </script>
    <style scoped>
      
    </style>