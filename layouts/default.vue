<template>
    <div>
      <Navbar />
      <Nuxt />
    </div>
  </template>
  
  <script>
  import Navbar from '~/components/inc/Navbar.vue'
  
  export default {
    name: 'default',
    components: {
      Navbar
    }
  }
  </script>
  