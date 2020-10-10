<template>
  <Layout>
    <v-row>
      <v-col cols="12" md="8" offset-md="2">
        <Carousel />
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="10" offset="1" md="10" offset-md="1">
        <LeadText />
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <Parallax />
      </v-col>
    </v-row>
    <br>
    <v-row >
      <v-col>
        <Services />
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <About />
      </v-col>
    </v-row>

    <footer>
        <Footer />

    </footer>


  </Layout>
</template>

<script>

import Carousel from "~/components/Carousel.vue";
import LeadText from "~/components/LeadText.vue";
import Parallax from "~/components/Parallax.vue";
import About from "~/components/About.vue";
import Footer from "~/components/Footer.vue";
import Services from "~/components/Services.vue";



export default {
  metaInfo: {
    title: "Home",
  },
  components: {
    Carousel,
    LeadText,
    Parallax,
    About,
    Footer,
    Services
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}

</style>
