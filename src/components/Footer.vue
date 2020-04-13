<template>
  <v-container class="hidden-sm-and-down">
    <v-divider></v-divider>
    <v-row align="left" justify="left">
      <v-col lg="2">
        <v-btn style="margin-bottom:20px;" text @click.native.stop="$vuetify.goTo('*', options)">
          <v-img
            alt="Dart Logo"
            class="shrink mr-2"
            contain
            src="./../assets/logo.png"
            transition="fab-transition"
            width="40"
          />
          <p class="headline pt-5">Abushakir</p>
        </v-btn>
        <v-list two-line>
          <v-list-tile>
            <v-list-tile-content>
              <v-list-tile-sub-title
                style="opacity:0.7"
              >Fugiat quis proident nulla proident id labore tempor voluptate do ea laborum et do.</v-list-tile-sub-title>
            </v-list-tile-content>
          </v-list-tile>
        </v-list>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "footer",

  data: () => ({})
};
</script>
