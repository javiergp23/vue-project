<template>
  <Navbar />
  
  <router-view/>
  

  <medios-pago/>

  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/services">Services</router-link> |
    <router-link to="/blog/entrada">Blog</router-link> 
  </nav>
  <router-view/> -->
  <Footer />
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
import MediosPago from '@/components/MediosPago.vue'
// import BlogView from '@/views/BlogView.vue'
// import AboutView from '@/views/AboutView.vue'
// import Servicios from '@/views/Servicios.vue'
export default {
  name: 'HomeView',
  components: {
    AboutView,
    Servicios,
    BlogView,
    NavBar,
    Footer,
    MediosPago
  }
}
</script>
