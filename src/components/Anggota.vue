<template>
     <div>
            <b-form-rating v-model="value" show-value></b-form-rating>
            <p class="teks mt-2">Value: {{ value }}</p>
        <b-container fluid>
                <h1 class="text-center mt-2">Crew Web</h1>
             <div>
                    <ul class="list-unstyled">
                        <b-media tag="li">
                        <template #aside>
                            <b-img blank blank-color="#abc" width="64" alt="placeholder"></b-img>
                        </template>
                        <h5 class="mt-0 mb-1">List-based media object</h5>
                        <p class="mb-0">
                            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.
                            Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc
                            ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                        </p>
                        </b-media>

                        <b-media tag="li" class="my-4">
                        <template #aside>
                        <b-img blank blank-color="#cba" width="64" alt="placeholder"></b-img>
                        </template>

                        <h5 class="mt-0 mb-1">List-based media object</h5>
                        <p class="mb-0">
                            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.
                            Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc
                            ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                        </p>
                        </b-media>

                        <b-media tag="li">
                        <template #aside>
                            <b-img blank blank-color="#bac" width="64" alt="placeholder"></b-img>
                        </template>

                        <h5 class="mt-0 mb-1">List-based media object</h5>
                        <p class="mb-0">
                            Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.
                            Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc
                            ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                        </p>
                        </b-media>
                    </ul>
                </div>
        </b-container>
  </div>
</template>

<script>
 export default {
    data() {
      return {
        value: 4
      }
    }
  }
</script>

<style scoped>
.teks{
    text-align: center;
    font-size: large;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
</style>