<template>
<div>
    <home-intro-1/>
    <home-col/>
   <slide-product/>
</div>
</template>

<script>
import HomeIntro from '~/components/Home-intro.vue'
import HomeIntro1 from '~/components/Home-intro1.vue'
import HomeCol from '~/components/Home-col.vue'
import SlideProduct from '~/components/slide-product.vue'
export default {
  components: { HomeIntro, HomeIntro1, HomeCol, SlideProduct },
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


