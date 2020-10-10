<template>
  <div>
      <div class="text-right">

    <a href='https://www.facebook.com/Arrowhead-Hauling-Junk-Removal-LLC-104178974757361"'> <v-icon> mdi-facebook</v-icon></a>
                  <a href='href="https://twitter.com/arrowhead_llc'> <v-icon> mdi-twitter</v-icon></a>
                  <a href='https://www.instagram.com/arrowhead_llc/'><v-icon> mdi-instagram</v-icon></a>
      

      </div>
    <v-carousel height="auto" cycle hide-delimiter-background show-arrows-on-hover>
      <v-carousel-item v-for="image in images" :key="image">
        <v-img :src="image"></v-img>
      </v-carousel-item>
    </v-carousel>
    <br />
  </div>
</template>


<script>
export default {
  data() {
    return {
      images: [
        "https://i.imgur.com/TGTjvQl.jpg",
        "https://i.imgur.com/3atPn4M.jpg",
        "https://i.imgur.com/k3WsF5n.jpg"
      ]
    };
  }
};
</script>

<style scoped>
.v-icon {
    margin: 10px;
    color: black;
}
a {
  text-decoration: none;
}

</style>