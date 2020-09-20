<template>
  <v-card
    class="pa-4"
    flat
    height="400px"
    img="foodimage.jpg"
  >
      
    <v-row align="center">
     <v-btn large>CATEGORY</v-btn>
      <v-col align="right">

        <v-btn text icon>
          <v-icon Normal color="black">mdi-magnify</v-icon>
        </v-btn>
        <v-btn text x-large color="black">OFFERS</v-btn>

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
      <v-col md="4" offset-md="4" >
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