<template>
  <v-app>
    <v-content>
      <v-parallax src="./assets/wow.png"></v-parallax>
      <h1>Thanksgivings 2018 - The convergence</h1>
      <v-container fluid>
        test
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import parallaxHeader from './components/ParallaxHeader.vue'

export default {
  name: 'app',
  components: {
    parallaxHeader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
