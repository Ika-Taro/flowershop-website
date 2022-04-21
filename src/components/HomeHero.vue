<template>
  <section class="home-hero">
    <v-container fluid fill-height class="home-hero__content">
        <div class="hero-logo">
          <v-img class="hero-logo-img"
          src= "../assets/flowershoplogo.jpg"
          height="200"
          width="200"
          ></v-img>
        </div>
    </v-container>
  </section>
</template>
<style  lang="scss" scoped>
.home-hero__content {
  background: url("../assets/flowershop-hero1.jpg");
  background-size: cover;
  background-position: center center;
  width: 100%;
  height: 100vh;
  position: relative;
}
.hero-logo {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: block;
}
</style>