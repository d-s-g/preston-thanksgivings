<template>
  <v-container>
    <v-card>
      <v-container>
        <v-container>
        <h1>Thanksgivings 2018 - The convergence</h1>
          <h3 class="pt-5">Attendees</h3>
            <ul>
                <li>Grandaddy</li>
                <li>Ann Reid</li>
                <li>Ad</li>
                <li>Leigh</li>
                <li>David</li>
                <li>Brac</li>
                <li>Margie</li>
                <li>Ann</li>
                <li>Brendan</li>
            </ul>
          <h2 class="pt-3">Are you attending?</h2>
          <p class="mb-0">Let me know here: <a href="mailto:david.stanford.gibson@gmail.com">Contact David</a></p>
        </v-container>
        <v-container>
          <h2>Meal</h2>
          <h3 class="pt-3">David</h3>
          <ul>
              <li>Turkey</li>
              <li>Mashed Potatoes</li>
              <li>Mushroom risotto</li>
          </ul>
          <h3>Ann Reid</h3>
          <ul>
              <li>Cheesecake</li>
              <li>Vegetables dish</li>
          </ul>
          <h3>Ad</h3>
          <ul>
            <li>Rolls</li>
          </ul>
          <h3>Brac</h3>
          <ul>
            <li>Vegetables dish</li>
          </ul>
          <div class="mt-5">
            <h2>Have</h2>
            <ul>
              <li>Main course</li>
              <li>5 sides</li>
              <li>1 Dessert</li>
            </ul>
            <h2 class="pt-3">Need</h2>
            <ul>
              <li>1 Dessert</li>
              <li>Appitisers</li>
              <li>Vegetable Main?</li>
            </ul>
            <h2 class="pt-3">What are you making?</h2>
            <p>Let me know here: <a href="mailto:david.stanford.gibson@gmail.com">Contact David</a></p>
          </div>
        </v-container>
      </v-container>
    </v-card>
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
