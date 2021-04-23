<template>
  <div id="app">
    <div>
    
    </div>
    <Navbar />
    <Box/>
    <Anggota/>
    <Coding/>
    <Footer/>
   
   
    
  </div>
</template>
<script> 
  import Navbar from './components/Navbar.vue';
  import Box from './components/Box.vue';
  import Anggota from './components/Anggota.vue';
  import Coding from './components/Coding.vue';
  import Footer from './components/Footer.vue';
 
  export default {
    name: 'navbar',
    components: {
      Navbar,
      Box,
      Anggota,
      Coding,
      Footer
    }
  }
</script>