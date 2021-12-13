<template>
  <div class="home">
    <h1>Homepage</h1>
    <p class="cyan  indigo--text text--darken-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima, sapiente. Debitis repudiandae officiis dolorum error blanditiis labore aliquam illo quas eligendi sapiente porro vero nesciunt, praesentium impedit saepe dolor numquam.</p>
    <p class="display-4 text-capitalize">Massive Display text</p>
    <v-btn class="blue white--text">Click</v-btn>
    <v-btn plain color="blue">CLick</v-btn>
    <v-btn depressed color="blue"> click</v-btn>

    <v-btn plain color="blue">
      Email
      <v-icon> mdi-email
      </v-icon>
    </v-btn>

    <v-btn class="blue darken-3 cyan--text text--lightn-5">Home
      <v-icon>mdi-home</v-icon>
    </v-btn>

    <v-btn>Fingerprint
      <v-icon>mdi-fingerprint</v-icon>
    </v-btn>
    
    <v-btn>Cell
      <v-icon> mdi-cellphone</v-icon>
    </v-btn>
  </div>
</template>

<script>
  
  export default {
    name: 'Home',

    components: {
    
    },
  }
</script>
