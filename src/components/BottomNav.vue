<template>
  
    <v-bottom-navigation fluid class="hidden-md-and-up" dark fixed >
      <v-btn text @click.native.stop="$vuetify.goTo('#about', options)">About<v-icon>mdi-code-tags</v-icon></v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#competition', options)">Competition <v-icon>mdi-code-tags</v-icon></v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#docs', options)">Docs <v-icon>mdi-code-tags</v-icon></v-btn>
      <v-btn text @click.native.stop="$vuetify.goTo('#contribute', options)">Contribute <v-icon>mdi-code-tags</v-icon></v-btn>
    </v-bottom-navigation>
  
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
