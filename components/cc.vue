<template>
  
  <v-container fluid>
    <v-row justify="center"
      class="mx-auto">
      <v-col
          
        v-for="card in cards"
        :cols="12" md="4"
      >
        <v-card>
          <v-img
            :src="card.src"
            class="white--text align-end"
            height="300px"
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