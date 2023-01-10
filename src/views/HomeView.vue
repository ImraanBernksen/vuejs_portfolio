<template>
  <NavBar/>
  <Home/>
  <Footer/>
</template>
<script>
import NavBar from '../components/NavBar.vue';
import Footer from '../components/Footer.vue';
import Home from '../components/Home.vue'
export default {
  name: 'HomeView',
  components: {
    NavBar,
    Footer,
    Home
  }
}
</script>
<style scoped>
  
</style>
