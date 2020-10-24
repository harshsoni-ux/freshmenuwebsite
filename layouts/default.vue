<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
    
    <!--Header -->
    
    <v-app-bar color="white" fixed app height="50">
      <FreshMenuLogo/>

      <v-spacer></v-spacer>
      
      <v-btn color=black icon>
      help
    </v-btn>


    <v-btn color=black icon >
      <v-icon >mdi-account</v-icon>
    </v-btn>
    
    </v-app-bar>
    
    
    
    <!--
     <v-app-bar color="white" dark fixed app>
      <v-toolbar-title>Application</v-toolbar-title>
        Component Example -->
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
    <Footer/>

  </v-app>
</template>
<style> 
   #inspire {
    background-color: white;
    color: black;
  }
  
</style>