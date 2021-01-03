<template>
<v-card elevation="4" shaped class="mx-auto ma-4">
    
   
    <v-sheet
    
    class="mx-auto ma-1"
  >
    <v-slide-group
      v-model="model"
      class="pa-4"
      active-class="success"
      show-arrows
    >
      <v-slide-item
        v-for="n in 10"
        :key="n"
      >

  <v-card
    hover
    class="ma-2"
    max-width="150"
    max-hight="100"
  >
    <v-img
    contain
    class="green lighten-4"
      src="https://firebasestorage.googleapis.com/v0/b/image-server-65bbd.appspot.com/o/restaurant%2Fimage_1609620325390.png?alt=media&amp;token=0e18dc48-ed57-468d-89bb-9625efa31da3&quot"
      height="100"
    >
 
    </v-img>


    <v-card-title>
      Top western road trips
    </v-card-title>
    <v-card-subtitle>
      1,000 miles of wonder
    </v-card-subtitle>

    <v-card-actions>

      <v-spacer></v-spacer>
    </v-card-actions>
  </v-card>
  
      </v-slide-item>
    </v-slide-group>
  </v-sheet>

   <div class="text-right">
      <v-btn
      class="mr-4 mb-4 "
      outlined
      color="primary"
    > Best Sales
        <v-icon
          dark
          right
        >
         mdi-arrow-right-bold-box-outline
        </v-icon>
    </v-btn>
  </div>

  </v-card>
</template>

<script>
  export default {
    data: () => ({
      model: null,
    }),
  }
</script>

<style>





