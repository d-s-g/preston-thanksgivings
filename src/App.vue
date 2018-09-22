<template>
  <v-app>
    <v-content>
      <parallaxHeader></parallaxHeader>
      <h1>Thanksgivings 2018 - The convergence</h1>
      <mealList></mealList>
    </v-content>
  </v-app>
</template>

<script>
import parallaxHeader from './components/ParallaxHeader.vue'
import mealList from './components/MealList.vue'

export default {
  name: 'app',
  components: {
    parallaxHeader,
    mealList
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
}
</style>
