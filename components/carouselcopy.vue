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
  
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { src: 'bestsellerimg.jpeg', flex: 4 },
        { src: 'bestsellerimg2.JPG', flex: 4 },
        { src: 'bestsellerimg3.jpg', flex: 4 },
        
      ],
    }),
  }
</script>