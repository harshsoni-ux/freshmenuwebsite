<template>
  <v-card
    class="pa-4"
    flat
    height="400px"
    img="Foodimage.jpg"
  >
    <v-toolbar 
      
      justify="center"
      dense
      floating
      color=white
    >
      <v-text-field
        hide-details
        color=black;
        single-line 
      ></v-text-field>

      <v-btn color=black icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>

      <v-btn color=black icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-toolbar>
  </v-card>
</template>