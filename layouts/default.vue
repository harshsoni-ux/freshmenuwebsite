<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
    
    <!--Header -->
    <densetoolbar/>
    
    <!--
     <v-app-bar color="white" dark fixed app>
      <v-toolbar-title>Application</v-toolbar-title>
       <!-- Component Example -->
    <!--
      <VuetifyLogo/>
      
    </v-app-bar> 
    -->

    <!-- Body -->
     
    <v-content light>
   
      <nuxt /> 
      
      <button/>
     
    </v-content>
    
    <!-- Footer -->
    <v-footer color="white" app>
      <span class="black--text">&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   /*#inspire {
    background-color: white;
    color: black;
  }
  */
</style>