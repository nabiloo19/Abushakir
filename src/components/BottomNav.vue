<template>
  <v-container>
    <v-bottom-navigation class="hidden-md-and-up" color="purple lighten-1">
      <v-btn text @click.native.stop="$vuetify.goTo('#about', options)">About</v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#competition', options)">Competition</v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#docs', options)">Docs</v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#contribute', options)">Contribute</v-btn>
    </v-bottom-navigation>
  </v-container>
</template>

<script>
export default {
  name: "toolbar",

  data: () => ({
    options: {
      duration: 750,
      offset: -10,
      easing: "easeInOutCubic"
    }
  })
};
</script>
