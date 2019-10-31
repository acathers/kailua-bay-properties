<template>
  <div class="navbar">
    <v-toolbar prominent src="https://www.slashgear.com/wp-content/uploads/2019/05/hawaii_cc0_unsplash-1280x720.jpg">
      <v-toolbar-title class="title">Kailua Bay Properties</v-toolbar-title>

      <v-spacer />

      <v-toolbar-items>
        <router-link tag="button" class="no-underline" to="/">
          <v-btn color="teal lighten-4">Home</v-btn>
        </router-link>
        <router-link tag="button" class="no-underline" to="/about">
          <v-btn color="teal lighten-4">New Listings</v-btn>
        </router-link>
        <router-link tag="button" class="no-underline" to="/about">
          <v-btn color="teal lighten-4" >Services</v-btn>
        </router-link>
        <router-link tag="button" class="no-underline" to="/about">
          <v-btn  color="teal lighten-4" >Coupon</v-btn>
        </router-link>
        <router-link tag="button" class="no-underline" to="/about">
          <v-btn  color="teal lighten-4" >Contact Us</v-btn>
        </router-link>

        <router-link tag="button" class="no-underline" to="/about">
          <v-btn color="teal lighten-4" >Meet Our Team</v-btn>
        </router-link>
      </v-toolbar-items>
    </v-toolbar>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "navbar"
};
</script>

<style scoped>
.no-underline {
  text-decoration: none;
}

.title {
    font-family:'Gill Sans' 
}
</style>