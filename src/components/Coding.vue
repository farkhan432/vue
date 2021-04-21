<template>
  <div>  
        <b-container fluid> 
        <h1 class="teks text-center mt-5">Menu Pilihan dan Promo </h1>
                <div>
                    <b-carousel
                        id="carousel-no-animation"
                        style="text-shadow: 0px 0px 2px #000"
                        no-animation
                        indicators
                        img-width="1024"
                        img-height="280"
                    >
                        <b-carousel-slide
                        caption="First slide"
                        img-src="https://picsum.photos/id/292/3852/2556"
                        ></b-carousel-slide>
                        <b-carousel-slide
                        caption="Second Slide"
                        img-src="https://picsum.photos/id/312/3888/2592"
                        ></b-carousel-slide>
                        <b-carousel-slide
                        caption="Third Slide"
                        img-src="https://picsum.photos/id/326/4928/3264"
                        ></b-carousel-slide>
                        <b-carousel-slide
                        caption="Fourth Slide"
                        img-src="https://picsum.photos/id/102/4320/3240"
                        ></b-carousel-slide>
                    </b-carousel>
                </div>      
                        
        </b-container>
    </div>
  


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
.teks{
    font-family: 'Times New Roman', Times, serif;
}

</style>