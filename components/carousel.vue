<template>
  <v-row>
  
  <v-carousel
    cycle
    height="350"
    hide-delimiter-background
    show-arrows-on-hover
    class="px-lg-6"
   
  >
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      
    >
      
      
      
      
    </v-carousel-item>
  </v-carousel>
  </v-row> 
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'bestsellerss.png',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          
        ],
      }
    },
  }
</script>