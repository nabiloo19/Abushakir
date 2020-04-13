<template>
  <v-container class="text-center" id="contribute">
    <h2 class="display-3 pt-12">Contribute</h2>
    <p
      class="text--secondary mt-4 mb-8"
    >Veniam ullamco laboris aliquip qui enim in exercitation dolor anim nulla proident irure aliqua consequat.</p>

    <v-container class="grey lighten-5">
      <v-row class="mb-6" justify="space-around" no-gutters>
        <v-col lg="2">
          <v-avatar color="indigo" size="110">
            <v-icon color="white" size="50">mdi-help</v-icon>
          </v-avatar>
          <p class="display-1 mt-3">Help</p>
          <p class="text--secondary mt-4">Veniam ullamco laboris.</p>
        </v-col>
        <v-col md="auto">
          <v-avatar color="indigo" size="110">
            <v-icon color="white" size="50">mdi-bell</v-icon>
          </v-avatar>
          <p class="display-1 mt-3">Notify</p>
          <p class="text--secondary mt-4">Veniam ullamco laboris.</p>
        </v-col>
        <v-col lg="2">
          <v-avatar color="indigo" size="110">
            <v-icon color="white" size="50">mdi-wrench</v-icon>
          </v-avatar>
          <p class="display-1 mt-3">Build Up</p>
          <p class="text--secondary mt-4">Veniam ullamco laboris.</p>
        </v-col>
      </v-row>
    </v-container>
    <v-btn class="mb-3" dark raised>
      <v-icon class="capitalize mr-2">mdi-check</v-icon>Make an impact
    </v-btn>
  </v-container>
</template>

<script>
export default {
  name: "Contribute",

  data: () => ({})
};
</script>
