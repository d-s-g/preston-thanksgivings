<template>
      <div class="bg"></div>
</template>

<script>
export default {
  name: 'parallaxHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .bg {
    background-image: url('../assets/wow.png');
    background-repeat: repeat;
    height: 500px;
    width: 100vw;
    background-attachment: fixed;
  }
</style>
