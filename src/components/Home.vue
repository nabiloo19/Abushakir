<template>
  <v-container class="text-center">
    <Intro />
    <About class="mt-12"/>
    <Competition />
    <Docs />
    <Contribute />

  </v-container>
</template>

<script>

import About from "./About";
import Intro from "./Intro";
import Contribute from "./Contribute";
import Competition from "./Competition";
import Docs from "./Docs";

export default {
  name: "Home",

  data: () => ({}),

  components: {
    About,
    Contribute,
    Competition,
    Docs,
    Intro
  }
};
</script>
