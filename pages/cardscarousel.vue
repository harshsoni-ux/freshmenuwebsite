<template>
  <v-sheet
    class="mx-auto"
    elevation="0"
    
    color="white"
  >
    <v-slide-group
     
    height="400"
    
    light
      
    >
      <v-slide-item
       v-for="(item,i) in items"
      :key="i"
      
      
        
      > 
      <v-col cols="1" lg="1" md="1" sm="1">
        <v-card
        
          color="white"
          class="ma-3 py-1"
          height="240"


          
          
          
          
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
            src: 'bestofferimg.jpeg',
          },
          {
            src: 'bestofferimg2.jpg',
          },
          {
            src: 'bestofferimg3.jpg',
          },
          {
            src: 'bestofferimg4.png',
          },
          {
            src: 'bestofferimg5.png',
          },
          {
            src: 'bestofferimg6.png',
          },
        ],
      }
    },
  }
</script>