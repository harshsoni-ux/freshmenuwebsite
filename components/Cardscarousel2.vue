<template>
  <v-sheet
    class="mx-auto"
    elevation="0"
    
    color="white"
  >
    <v-slide-group
    active-class="success"
    height="400"
    v-model="model"
    show-arrows
    light
      
    >
      <v-slide-item
       v-for="item in items"
      
      
      
        
      > 
      <v-col cols="1" lg="1" md="1" sm="1">
        <v-card
        
          color="white"
          class="ma-2 py-1 "
          height="240"
          max-width="750"


          
          
          
          
        >
        
          <v-img
            :src="item.src"
          >
          </v-img>

          
        </v-card>
        </v-col>
      </v-slide-item>
    </v-slide-group>
  </v-sheet>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'bestsellerimg.jpeg',
          },
          {
            src: 'bestsellerimg2.jpg',
          },
          {
            src: 'bestsellerimg3.jpg',
          },
          {
            src: 'bestsellerimg4.png',
          },
          {
            src: 'bestsellerimg5.png',
          },
          {
            src: 'bestsellerimg6.png',
          },
        ],
      }
    },
  }
</script>