<template>
  <span>
    <!-- <Navbar /> -->
    <Hero />
  </span>
</template>

<script>
// import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Hero
  }
}
</script>

<style>
#apps {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
