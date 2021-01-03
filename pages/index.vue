<template>
  <v-container>
   <home-intro/>

      <div>
      <h1></h1> 
      <h1>find Us</h1> 
    </div>
   
  </v-container>
</template>

<script>
import HomeIntro from '~/components/Home-intro.vue'
export default {
  components: { HomeIntro },
    data: () => ({
     
    }),
  }
</script>

<style>
.slider-background {
  background-color: rgba(80, 80, 80, 0.493);
  width: 100%;
  height: 40%;
  text-align: center;
  margin-top: auto;
  padding-top: 20px;
}

@media screen and (min-width: 601px) {
  slider-background {
    font-size: 65px;
  }
}

@media screen and (max-width: 600px) {
  slider-background {
    font-size: 30px;
  }
  @media only screen and (max-width: 600px) {
    body {
      background-color: lightblue;
    }
  }
}

     
</style>


