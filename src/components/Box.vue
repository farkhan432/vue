<template>
    <b-container-fluid class="bv-example-row">
  <b-row class="text" align-h="">
        <b-col class=" box bg-danger" cols="4">One of two columns</b-col> 
        <b-col class="box bg-warning" cols="4">One of two columns</b-col>
        <b-col class="box bg-primary"  cols="4">One of two columns</b-col>
  </b-row>

 

  <b-row align-h="end">
    <b-col cols="4">One of two columns</b-col>
    <b-col cols="4">One of two columns</b-col>
  </b-row>

  <b-row align-h="around">
    <b-col cols="4">One of two columns</b-col>
    <b-col cols="4">One of two columns</b-col>
  </b-row>

  <b-row align-h="between">
    <b-col cols="4">One of two columns</b-col>
    <b-col cols="4">One of two columns</b-col>
  </b-row>
</b-container-fluid>
</template>

<script>
export default{
    data(){
       return{

       };
    },
}
</script>

<style scoped>
.box {
   height: 100px;
}
.text{
    text-align: center;
}
</style>
