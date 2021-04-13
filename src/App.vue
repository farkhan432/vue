<template>
  <div id="app">
    <div>
    
    </div>
    <Navbar />
    <Box/>
    
  </div>
</template>
<script> 
  import Navbar from './components/Navbar.vue';
  import Box from './components/Box.vue';
  export default {
    name: 'navbar',
    components: {
      Navbar,
      Box
    }
  }
</script>