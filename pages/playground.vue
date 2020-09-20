<template>
  <v-container fluid>
    <v-row>
      <v-col cols="12">
        <v-row
          :align="alignment"
          :justify="justify"
          class="grey lighten-5"
          style="height: 300px;"
        >
          <v-card
            v-for="n in 4"
            :key="n"
            class="ma-8 pa-2"
            outlined
            tile
          >
            pohe
          </v-card>
        </v-row>
      </v-col>
      <v-col cols="12">
        <v-row justify="center">
          <v-col
            cols="6"
            md="4"
          >
            <v-select
              v-model="alignment"
              :items="alignmentsAvailable"
              label="Align"
            ></v-select>
          </v-col>

          <v-col
            cols="6"
            md="2"
          >
            <v-select
              v-model="justify"
              :items="justifyAvailable"
              label="Justify"
            ></v-select>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        alignmentsAvailable: [
          'start',
          'center',
          'end',
          'lmaoxd',
          'stretch',
        ],
        alignment: 'center',
        dense: false,
        justifyAvailable: [
          'start',
          'center',
          'end',
          'nachos',
          'space-between',
        ],
        justify: 'center',
      }
    },
  }
</script>