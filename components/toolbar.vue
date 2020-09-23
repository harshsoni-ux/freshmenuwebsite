<template>
  <v-card
    class="pa-4"
    flat
    height="400px"
    img="foodimage.jpg"
  >
      
    <v-row align="center">
      <v-col 
        :cols="12" lg="4" md="4" sm="4">
        <v-btn height="40" min-width="40" top class="yellow darken-2 mt-lg-n13 ml-lg-n5 mt-md-n13 ml-md-n5 rounded-0 " >CATEGORY</v-btn>
      </v-col>
      <v-col align="right"
        :cols="12" lg="4" md="4" sm="4" offset-md="4" offset-sm="4">

        <v-btn text icon >
          <v-icon Normal class="grey-lighten-5 mt-lg-n12  mt-md-n16 ml-md-n4">mdi-magnify</v-icon>
        </v-btn>

        <v-icon text small class="grey-lighten-5 mt-lg-n12 ml-lg-n1 mt-md-n16 ml-md-n2 text-body1 font-weight-medium">OFFERS</v-icon>

      </v-col>
    </v-row>

      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
        
    <v-row align="end">
      <v-col lg="4" md="4" sm="4" offset-md="4" offset-sm="4">
        <v-text-field centered="false"
          hide-details 
          label="Filled" 
          placeholder="Location" 
          solo
          color="white"
          light
          rounded 
          dense 
          single-line 
          append-icon="mdi-magnify" class="shrink"> 
        </v-text-field>
      </v-col>
    </v-row>

          

       
     
  </v-card>
</template>