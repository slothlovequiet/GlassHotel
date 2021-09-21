<template>
<div id="app">
<v-carousel
   :carousel_data="sliderItems"
/>
</div>
</template>
<script>
import vCarousel from 'JS/v-carousel.vue'
export default {
   name: 'app',
   components: {
      vCarousel
   },
data() {
    return {
       sliderItems: [
            id: 1, name: 'intro1', img: 'Images/index/Intro.svg',
            id: 2, name: 'intro2', img: 'Images/intro2.jpg',
      ], 
   },
},
},
</script>