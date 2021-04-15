<template>
    <div>
      <b-navbar toggleable="lg" type="dark" variant="success">
        <b-container fluid>
            <b-navbar-brand href="#" class="judul">Ini Toko +62</b-navbar-brand>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
             <b-navbar-nav class="ml-auto">
                <b-nav-item right>
                  <!-- Using 'button-content' slot -->
                    <b-navbar-nav>
                      <b-nav-item active href="#" class="text"> Home </b-nav-item>
                      <b-nav-item href="#" class="text"> Tentang </b-nav-item>
                      <b-nav-item href="#" class="text"> Kontak </b-nav-item>
                    </b-navbar-nav>
                </b-nav-item>
              </b-navbar-nav>
            
              <!-- Right aligned nav items -->
              <b-navbar-nav class="ml-auto">
                <b-nav-form>
                  <b-form-input 
                    size="sm" 
                    class="mr-sm-2" 
                    placeholder="Carilah"
                    v-model="meal"
                    ></b-form-input>
                  <b-button 
                    size="sm" 
                    class="my-2 my-sm-0" 
                    type="Tekan" 
                    @click.prevent="getMeal"
                    >Cari</b-button>
                </b-nav-form>
                <b-nav-item-dropdown right>
                  <!-- Using 'button-content' slot -->
                  <template slot="button-content"><em>Pengguna</em></template>
                  <b-dropdown-item href="#">Profile</b-dropdown-item>
                  <b-dropdown-item href="#">Keluar</b-dropdown-item>
                </b-nav-item-dropdown>
              </b-navbar-nav>
            </b-collapse>
          </b-container>
      </b-navbar>
    </div>  
</template>
<script>
export default {
    data() {
        return {
            meal: ''
        }
    },
  methods: {
    getMeal() {
      
    }
  }
}    
</script>
<style scoped>
.text{
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
}
.judul{
  font-family: Arial, Helvetica, sans-serif;
  font-size: 28px;
}
</style>