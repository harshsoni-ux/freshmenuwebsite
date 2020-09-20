<template>
  <v-container class="grey lighten-5">
    <!-- Stack the columns on mobile by making one full-width and the other half-width -->
    <v-row>
      <v-col
        cols="12"
        md="8"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          .col-12 .col-md-8
        </v-card>
      </v-col>
      <v-col
        cols="6"
        md="4"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
        <!-- in first row for-loop hasn't been used.. colums hav been given individual attributes-->
        <!-- cols="_" is telling to occupy that many colums and if it isn't able to do so then md="_" tells it what the size should be (when screen is small)-->
          .col-6 .col-md-4
        </v-card>
      </v-col>
    </v-row>

    <!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
    <v-row>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="4"
        md="5"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
        <!-- in this row, for-loop has been used so the attributes asigned are applied to all (n=_)-->
          .col-6 .col-md-4
        </v-card>
      </v-col>
    </v-row>

    <!-- Columns are always 50% wide, on mobile and desktop -->
    <v-row>
      <v-col
        v-for="n in 2"
        :key="n"
        cols="4"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          .col-6
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>