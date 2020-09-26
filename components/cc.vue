<template>
  
  <v-container fluid>
    <v-row class="mx-auto">
      <v-col
        :cols="12" lg="4" md="4" sm="6"
      > <!--need to define column occupancy for all screen sizes in order to keep it responsive-->
        <v-card height="280px" class="d-lg-flex py-sm-4 py-lg-0 py-md-7 py-5"> <!--flex means visibility and py,px,pt etc is for padding-->
          <v-img
            src="bestofferimg.jpeg"
            
            
          >
              
          </v-img>

            
        </v-card>
      </v-col>
      <v-col
        :cols="12" lg="4" md="4" sm="6"
      >
        <v-card height="280px" class="d-none d-sm-flex d-md-flex d-lg-flex py-sm-3 py-lg-0 py-md-7 ">
          <v-img
            src="bestofferimg2.jpg"
            
            
          >
              
          </v-img>

            
        </v-card>
      </v-col>
      <v-col
        :cols="12" lg="4" md="4" sm="6"
        class=".d-none .d-sm-flex .d-sm-none .d-md-flex"
      >
        <v-card height="280px" class="d-none d-md-flex d-lg-flex py-sm-0 py-lg-0 py-md-7">
          <v-img
            src="bestofferimg3.jpg"
            
            
          >
              
          </v-img>

            
        </v-card>
      </v-col>
    </v-row>
  </v-container>
  
</template>

<script>
 
</script>