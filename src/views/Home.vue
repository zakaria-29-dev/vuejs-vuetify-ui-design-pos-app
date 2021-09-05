<template>
  <v-app id="inspire">
   
   <SideBarLeft />
   <SideBarRight />

    
      <v-container>
       <v-toolbar  flat class="">
         <v-row>
           <v-col cols="12" sm="10">
             <v-text-field label="Search"  
           filled 
           rounded
           dense
           solo
           flat
           background-color="grey lighten-3"
         
           ></v-text-field>
           </v-col>
           <v-col cols="12" sm="2">
               <v-btn class="">
        <v-icon>fas fa-filter</v-icon> Filter
      </v-btn>
           </v-col>
         </v-row>
           
      </v-toolbar>
       
     <v-row class="mt-n9">
         <v-col cols="12" sm="6" >
            <v-toolbar class="" flat >
                <h5>My Filtres:</h5>
                <v-icon class="ml-1" small>fas fa-car-side</v-icon>
                <h5 class="ml-1">First Meal</h5>
                <v-chip
                class="ma-2"
                color="green"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon>fas fa-running</v-icon>
                </v-avatar>
                After Training
                </v-chip>
                <v-spacer></v-spacer>
                <h6 class="green--text">ADD</h6>
    </v-toolbar>
         </v-col>
          <v-col cols="12" sm="6">
            <v-toolbar class="" flat >
                <h5>Popular Filtres:</h5>
                <v-icon class="ml-1" small>fas fa-child</v-icon>
                <h5 class="ml-1">Slim Waist</h5>
                <v-spacer></v-spacer>
                <v-icon class="ml-1" small>fas fa-birthday-cake</v-icon>
               <h5 class="ml-1">Diet</h5>
     </v-toolbar>
         </v-col>
       </v-row>
       <v-toolbar class="pl-0 mt-n7" flat>
                <h4>345</h4>
                <h4 class="grey--text text--lighten-1 ml-2">Meals found</h4>
                <v-spacer></v-spacer>
                <h4 class="grey--text text--lighten-1 ">Sorted by:</h4>
                <h4 class="ml-1">Recommended</h4>
               <v-icon class="ml-1" small >fas fa-chevron-down</v-icon>
    </v-toolbar>
    <v-row class="mt-n6">
      <v-col cols="12" sm="4">
        <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="red lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                4.2
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon >
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="0.png" max-height="180" max-width="180"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)">
                <h5 class="ml-1 grey--text text-lighten-3">Cabage Salad</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                250g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$4.99</h5> 
            </v-card>
          </v-hover>
      </v-col>
      <v-col cols="12" sm="4">
        <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="blue lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                4.5
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon >
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="1.png" max-height="180" max-width="180"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)">
                <h5 class="ml-1 grey--text text-lighten-3">Noodle salad</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                300g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$6.30</h5> 
            </v-card>
          </v-hover>
      </v-col>
      <v-col cols="12" sm="4">
         <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="green lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                5.0
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon >
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="3.png" max-height="180" max-width="180"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)" class="mt-2">
                <h5 class="ml-1 grey--text text-lighten-3">Vegetable mix</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                400g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$5.99</h5> 
            </v-card>
          </v-hover>
      </v-col>
      <v-col cols="12" sm="4">
        <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="teal  lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                4.4
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon >
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="4.png" max-height="180" max-width="180"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)">
                <h5 class="ml-1 grey--text text-lighten-3">Seafood soup</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                350g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$6.10</h5> 
            </v-card>
          </v-hover>
      </v-col>
      <v-col cols="12" sm="4">
        <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="pink lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                5.0
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon color="red">
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="2.png" max-height="180" max-width="180"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)">
                <h5 class="ml-1 grey--text text-lighten-3">Bean Soup</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                300g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$4.30</h5> 
            </v-card>
          </v-hover>
      </v-col>
      <v-col cols="12" sm="4">
         <v-hover v-slot="{ hover }" open-delay="200">
            <v-card color="purple lighten-5" :elevation="hover ? 16 : 2">
               <v-app-bar flat color="rgba(0,0,0,0)">
                 <v-chip
                class="ma-2"
                color="black"
                text-color="white"
                dense
              >
                <v-avatar left>
                  <v-icon color="yellow">fas fa-star</v-icon>
                </v-avatar>
                4.7
                </v-chip>
                <v-spacer></v-spacer>
                
               <v-btn
                class=""
                fab
                
                x-small
                color="white"
              >
      <v-icon >
       far fa-heart
      </v-icon>
    </v-btn>
               </v-app-bar>
               <div class="d-flex flex-column justify-space-between align-center">
                 <v-img src="8.png" max-height="180" max-width="180" class="mt-n5"></v-img>
               </div>
                <v-app-bar flat color="rgba(0,0,0,0)" class="mt-n6">
                <h5 class="ml-1 grey--text text-lighten-3">Stewed vegetables</h5>
                <v-chip
                class="ma-2"
                color="grey lighten-3"
                text-color="red"
                dense
              >
                400g
                </v-chip>       
                </v-app-bar>
               <h5 class="ml-5 mt-n5">$4.99</h5> 
            </v-card>
          </v-hover>
      </v-col>
    </v-row>
    <div class="d-flex flex-column justify-space-between align-center">
       <v-btn
                    class="px-15 mt-2"
                    rounded
                    outlined
                    color="green"
                    dark
                    
                    >
                    <v-icon class="mr-1">
                      fas fa-spinner
                    </v-icon>
                   Load More
                    </v-btn>
    </div>
    </v-container>
      
     
   


  </v-app>
</template>

<script>
import SideBarLeft from '../components/SideBarLeft.vue';
import SideBarRight from '../components/SideBarRight.vue';
  export default {
    components: {
    SideBarLeft,
    SideBarRight,
  },
    data: () => ({ drawer: null }),
  }
</script>