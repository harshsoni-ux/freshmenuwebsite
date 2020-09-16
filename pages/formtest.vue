<template>
  <v-row justify="center">
    <v-dialog v-model="dialog" persistent max-width="600px">
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="primary"
          dark
          v-bind="attrs"
          v-on="on"
        >
          himmat hai toh touch kar
        </v-btn>
      </template>
      <v-card>
        <v-card-title>
          <span class="headline">ranbir singh</span>
        </v-card-title>
        <v-card-text>
          <v-container>
            <v-row>
              <v-col cols="6" md="4">
                <v-text-field label="gunja sa" required></v-text-field>
              </v-col>
              <v-col cols="12" md="2">
                <v-text-field label="hai koi" hint="hmmmmmmm"></v-text-field>
              </v-col>
              <v-col cols="12" sm="2">
                <v-text-field
                  label="ek tara"
                  hint="(ek tara)"
                  persistent-hint
                  required
                ></v-text-field>
              </v-col>
              <v-col cols="6">
                <v-text-field label="Email me*" required></v-text-field>
              </v-col>
              <v-col cols="6">
                <v-text-field label="Password yaad hai?*" type="password" required></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-select
                  :items="['hm', 'hmm', 'hmmm', 'hmmmm']"
                  label="Age*"
                  required
                ></v-select>
              </v-col>
              <v-col cols="12" sm="6">
                <v-autocomplete
                  :items="['Skiing', 'Ice hockey', 'Soccer', 'Basketball', 'Hockey', 'Reading', 'Writing', 'Coding', 'Basejump']"
                  label="free time me kya krte ho"
                  multiple
                ></v-autocomplete>
              </v-col>
            </v-row>
          </v-container>
          <big>indicates required field</big>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn color="blue darken-1" text @click="dialog = false">Close</v-btn>
          <v-btn color="blue darken-1" text @click="dialog = false">Save</v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </v-row>
</template>

<script>
  export default {
    data: () => ({
      dialog: false,
    }),
  }
</script>