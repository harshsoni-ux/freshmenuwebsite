<template>
  
  <v-container fluid>
    <v-row justify="center"
      class="mx-auto">
      <v-col
          
        v-for="card in cards"
        :cols="12" lg="4" md="4" sm="6"
      >
        <v-card>
          <v-img
            :src="card.src"
            
            height="280px"
          >
              
          </v-img>

            
        </v-card>
      </v-col>
    </v-row>
  </v-container>
  
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { src: 'bestofferimg.jpeg' },
        { src: 'bestofferimg2.jpg' },
        { src: 'bestofferimg3.jpg'  },
        
      ],
    }),
  }
</script>