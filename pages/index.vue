<template>
  
  <v-content>
    <toolbar/>
    <br>
    <v-row>
      <v-col>
       <v-text class="text-body1 ml-2 text-decoration-underline" color="black"> BEST OFFERS</v-text>
      </v-col> <!--text-body1 defines the size of the text-->
    </v-row>
    <Cardscarousel/>
    <br>
    <v-divider color="black"></v-divider>
    <br>
     

    <v-row>
      <v-col>
       <v-text class="text-body1 ml-2 text-decoration-underline" color="black"> BEST SELLERS</v-text>
      </v-col> <!--text-body1 defines the size of the text-->
    </v-row>
    <Cardscarousel2/>
    <br>
    <v-divider color="black"></v-divider> 
    <br>
    <br>

    <section id="categories"> <!-- this id is a follow up of 'href=#categories' in the toolbar compoent-->
      <v-row>
        <v-col>
        <v-text class="text-body1 ml-2 text-decoration-underline" color="black"> CATEGORIES</v-text>
        </v-col> <!--text-body1 defines the size of the text-->
      </v-row>
      <Cardscopy3/> 
    </section>
  </v-content>
  
</template>

<script>
</script>

<style> 
</style>