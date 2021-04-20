<template>
  <div id="app">
    <div>
    
    </div>
    <Navbar />
    <Box/>
    <Coding/>
    <Anggota/>
    
  </div>
</template>
<script> 
  import Navbar from './components/Navbar.vue';
  import Box from './components/Box.vue';
  import Coding from './components/Coding.vue';
  import Anggota from './components/Anggota.vue';
  export default {
    name: 'navbar',
    components: {
      Navbar,
      Box,
      Coding,
      Anggota
    }
  }
</script>