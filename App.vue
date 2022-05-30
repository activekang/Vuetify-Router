<template>
  <v-app>
      <span>Vuetify</span>
      <v-btn><router-link to="/">Home</router-link></v-btn>
      <v-btn><router-link to="/about">About</router-link></v-btn>
      <v-btn><router-link to="/port">Portfolio</router-link></v-btn>
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
//import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
   // HelloWorld
  },
  data() {
    return {
      //
    };
  }
};
</script>