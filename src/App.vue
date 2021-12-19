<template>
  <v-app>
    <Navbar/>

    <v-main>
      <router-view/>
    </v-main>

    <FooterApp/>
  </v-app>
</template>

<script>

import Navbar from "@/components/Navbar";
import FooterApp from "@/components/FooterApp";
export default {
  name: 'App',
  components: {FooterApp, Navbar},
  data: () => ({
    //
  }),
};
</script>
