<template>
  <v-container>
    <Intro />
    <About style="margin-top:120px" />
    <Competition />
    <Docs />
    <Contribute />
    <Footer />
    <BottomNav />
  </v-container>
</template>

<script>
import About from "./About";
import Intro from "./Intro";
import Contribute from "./Contribute";
import Competition from "./Competition";
import Docs from "./Docs";
import Footer from "./Footer";
import BottomNav from "./BottomNav";

export default {
  name: "Home",

  data: () => ({}),

  components: {
    About,
    Contribute,
    Competition,
    Docs,
    Intro,
    Footer,
    BottomNav
  }
};
</script>
