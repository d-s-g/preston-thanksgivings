<template>
    <v-container>
        <h1>Thanksgivings 2018 - The convergence</h1>
        <h3>David</h3>
        <ul>
            <li>Turkey</li>
            <li>Mashed Potatoes</li>
            <li>Mushroom risotto</li>
        </ul>
        <h2>What are you making?</h2>
        <p>Let me know here: <a href="mailto:david.stanford.gibson@gmail.com">Contact David</a></p>
    </v-container>
</template>

<script>
export default {
  name: 'mealList',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
}
h2,h3 { 
    margin: 20px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
}
li:not(:first-child) {
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
