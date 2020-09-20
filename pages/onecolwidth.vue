<template>
  <v-container class="red">
    <v-row
      class="mb-6"
      no-gutters
    >
      <v-col
        v-for="n in 3"
        :key="n"
        :cols="n === 2 ? 6 : undefined"
      >
      
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 3 {{ n === 2 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
        v-for="n in 4"
        :key="n"
        :cols="n === 1 ? 3 : undefined"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 4 {{ n === 2 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
    
    <v-row
      class="mb-4"
      no-gutters
    >
      <v-col
        v-for="n in 5"
        :key="n"
        :cols="n === 1 ? 6 : undefined"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ n }} of 5 {{ n === 1 ? '(wider)' : '' }}
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>