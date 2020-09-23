<template>
  
  <v-container fluid>
    <v-row justify="center"
      class="mx-auto">
      <v-col
        v-for="card in cards"
        :key="card.title"
        :cols="12" lg="4" md="4" sm="6" 
       >
        <v-card>
          <v-img
            :src="card.src"
            class="white--text"
            blur
            height="180px"
          >
            <v-card-title  v-text="card.title" class="text-h5 font-weight-medium"></v-card-title>
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
        { title: 'INDIAN THALI', src: 'indianthali.jpeg' },
        { title: 'CONTINENTAL', src: 'continental.jpeg' },
        { title: 'FIT & FAB', src: 'fit&fab.jpg'},
        { title: 'WOK STATION', src: 'wok.jpeg' },
        { title: 'BIG BIRYANI CO.', src: 'biryani.jpg' },
        { title: 'PIZZAS', src: 'pizza.jpg',  },
        { title: 'SNACKS', src: 'snacks.jpeg' },
        { title: 'BEVERAGE', src: 'beverage.jpg'},
        { title: 'DESSERT', src: 'dessert.jpeg' },
        
      ],
    }),
  }
</script>