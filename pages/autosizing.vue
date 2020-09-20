<template>
  <v-container class="red">
    <v-row
      v-for="n in 15"
      :key="n"
      :class="n === 5 ? 'mb-3' : ''"
      no-gutters
    >
      <v-col
        v-for="k in n + 6"
        :key="k"
      >
        <v-card
          class="pa-2"
          outlined
          tile
        >
          {{ k }} of {{ n + -2 }}
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>