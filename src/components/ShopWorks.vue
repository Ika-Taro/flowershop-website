<template>
  <v-container class="img-h"><v-carousel
  >
    
      <div class="carousel-item">
        <v-carousel-item 
          v-for="(item,i) in items"
          :key="i"
          :src="item.src"
        ></v-carousel-item>
      </div>
    
  </v-carousel></v-container>
</template>


<script>
  export default {
    data () {
      return {
        items: [
          {
            src: require('@/assets/flowershop-slide1.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide2.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide3.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide4.jpg'),
          },
        ],
      }
    },
  }
</script>

<style  lang="scss" scoped>
  .carousel-item {
    object-fit: cover;
  }
</style>