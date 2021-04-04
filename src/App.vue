<template>
  <span>
    <!-- <Navbar /> -->
    <Hero />
    <StepOne />
    <Keuntungan />
    <Daftar />
    <Mitra />
    <Footer />
  </span>
</template>

<script>
import Footer from './components/Footer.vue'
import Hero from './components/Hero.vue'
import StepOne from './components/StepOne.vue'
import Keuntungan from './components/Keuntungan.vue'
import Daftar from './components/Daftar.vue'
import Mitra from './components/Mitra.vue'

export default {
  name: 'App',
  components: {
    Hero,
    StepOne,
    Keuntungan,
    Daftar,
    Mitra,
    Footer
  }
}
</script>