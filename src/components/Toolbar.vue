<template>
  <v-container>
    <v-app-bar app light  fixed elevate-on-scroll>
      <div class="d-flex align-center">
        <v-btn text @click.native.stop="$vuetify.goTo('*', options)">
          <v-img
            alt="Dart Logo"
            class="shrink mr-2"
            contain
            src="./../assets/logo.png"
            transition="fab-transition"
            width="40"
          />Abushakir
        </v-btn>
      </div>

      <v-spacer></v-spacer>

      <div class="hidden-sm-and-down">
        <v-btn text @click.native.stop="$vuetify.goTo('#about', options)">About</v-btn>
        <v-btn text @click.native.stop="$vuetify.goTo('#competition', options)">Competition</v-btn>
        <v-btn text @click.native.stop="$vuetify.goTo('#docs', options)">Docs</v-btn>
        <v-btn text @click.native.stop="$vuetify.goTo('#contribute', options)">Contribute</v-btn>
      </div>
    </v-app-bar>
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
