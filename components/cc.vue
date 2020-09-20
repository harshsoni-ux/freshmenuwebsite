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
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { src: 'bestofferimg.jpeg' },
        { src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg' },
        { src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg'  },
        
      ],
    }),
  }
</script>