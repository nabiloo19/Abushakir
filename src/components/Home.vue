<template>
  <v-container class="text-center">

    <About />
    <Competition />
    <Docs />
    <Contribute />

  </v-container>
</template>

<script>

import About from "./About";
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
    Docs
  }
};
</script>
