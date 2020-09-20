<template>
  <v-container class="grey lighten-5">
    <v-row
      class="mb-6"
      no-gutters
    >
      <v-col
        v-for="n in 4"
        :key="n"
        :cols="n === 2 ? 6 : 3" 
      >
      <!-- 2nd part is 6 colums wide (6:3) rest of the parts are 3 colums wide -->
        <v-card
          class="pa-2"
          tile
          outlined
        >
          tanna
        </v-card>
      </v-col>
    </v-row>

    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 1 ? 4 : 8"
      >
        <v-card
          class="pa-2"
          tile
          outlined
        >
          col-{{ n === 1 ? 4 : 4 }}
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>