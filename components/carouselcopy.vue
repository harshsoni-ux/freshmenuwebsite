<template>
  

    <v-container fluid>
      <v-row justify="center"
       class="mx-auto">
        <v-col
          v-for="card in cards"
          :cols="card.flex"
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
        { src: 'bestsellerimg.jpeg', flex: 4 },
        { src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 4 },
        { src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 4 },
        
      ],
    }),
  }
</script>