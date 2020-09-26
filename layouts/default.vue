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
    <v-row>
      
      <v-footer 
        absolute
        app
        color="grey-darken" 
        > 
        <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
        <v-container>
          <v-row>
            <v-col
              cols="12"
              sm="3"
              md="3"
              >
              <h4>COMPANY</h4>
                
              <v-divider></v-divider>
              <br>
              <font size="2">FAQ<br><br>
              About<br><br>
              Careers<br><br>
              Blog<br><br></font>
            </v-col>
            <v-col
              cols="12"
              sm="3"
              md="3"
              lg="3"
              >
              <h4>HELP & CONTACT</h4>
              <v-divider></v-divider>
              <br>
              <font size="2"><v-icon>mdi-target</v-icon>Help Center<br><br>
              <v-icon>mdi-email</v-icon>Email Us<br><br>
              <v-icon>mdi-phone</v-icon>080-6824-5911<br><br></font>
              
            </v-col>
            <v-col
              cols="12"
              sm="3"
              md="3"
              >
            <h4>MORE FROM US</h4>
              <v-divider></v-divider>
              <br>
              <font size="2">Bulk/Party Order<br><br>
              Cake Order<br><br>
              FreshClub<br><br>
              Offers<br></br></font>
            </v-col>
                

            <v-col
              cols="12"
              sm="3"
              md="3"
              >
              <h4>CONTACT US</h4>
              <v-divider></v-divider><br>
              <v-row>
                <v-btn icon color="grey" class="mt-16">
                  <v-icon medium>mdi-facebook</v-icon>
                </v-btn>
                <v-btn icon color="grey"class="mt-16">
                  <v-icon medium>mdi-twitter</v-icon>
                </v-btn>
                <v-btn icon color="grey" class="mt-16">
                  <v-icon medium>mdi-instagram</v-icon>
                </v-btn>
              </v-row>
            </v-col>
          </v-row>
        </v-container>
      </v-footer>
      
    </v-row>

  </v-app>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-instagram',
      ],
    }),
  }
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   #inspire {
    background-color: grey;
    color: black;
  }
  
</style>