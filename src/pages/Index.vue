<template>
  <Layout>
    <v-row>
      <v-col class="text-center" lg="6" offset-lg="0" cols="10" offset="1">
        <h1>(989) 388-1697</h1>
        <h2>Call for a free quote!</h2>
        <br />
        <v-img src="https://i.imgur.com/SLPWzSn.jpg"></v-img>
      </v-col>
      <v-col
        order-lg="first"
        class="text-center mt-lg-16"
        lg="2"
        offset-lg="1"
        cols="12"
        offset="0"
      >
        <h2>Clean Outs</h2>
        <hr />
        <br />
        <p>Estate</p>
        <p>Tenant Eviction</p>
        <p>Garage</p>
        <p>Pole Barns</p>
        <p>Storage Units</p>
        <p>Attics</p>
        <p>Senior Centers</p>
      </v-col>
      <v-col class="text-center mt-lg-16" lg="2" offset-lg="0" cols="12" offset="0">
        <h2>Cleanups</h2>
        <hr />
        <br />
        <p>Storm Blow Downs</p>
        <p>Building Blow Downs</p>
        <p>Construction Material</p>
      </v-col>
    </v-row>
    <v-row order="2" height="10vh">
      <v-col lg="2" offset-lg="3" class="my-auto text-center">
        <h3>We haul junk...</h3>
      </v-col>
      <v-col lg="2" cols="12">
        <v-img class="my-auto mx-auto" width="20vh" src="https://i.imgur.com/wY4yfI4.png"></v-img>
      </v-col>
      <v-col lg="2" class="my-auto text-center">
        <h3>so you don't have to!</h3>
      </v-col>
    </v-row>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}

h3 {
  color: #fff201;
  font-family: "Myriad Pro Light", "Times New Roman", Times, serif;
  font-size: 1.4rem;
}

h2 {
  color: #fff201;
  font-family: "Myriad Pro Light", "Times New Roman", Times, serif;
}

h1 {
  color: #fff201;
  font-size: 46px;
  font-family: "Myriad Pro Light", "Times New Roman", Times, serif;
}

hr {
  border-color: #211d20;
}

p {
  color: #fff201;
  font-family: "Myriad Pro", "Times New Roman", Times, serif;
  font-size: 1.2rem;
}
</style>
