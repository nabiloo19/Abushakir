<template>
  <v-container >
    <Intro />
    <About style="margin-top:120px"/>
    <Competition />
    <Docs />
    <Contribute />
    <Footer />

  </v-container>
</template>

<script>

import About from "./About";
import Intro from "./Intro";
import Contribute from "./Contribute";
import Competition from "./Competition";
import Docs from "./Docs";
import Footer from "./Footer";

export default {
  name: "Home",

  data: () => ({}),

  components: {
    About,
    Contribute,
    Competition,
    Docs,
    Intro,
    Footer
  }
};
</script>
