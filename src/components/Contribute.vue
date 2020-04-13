<template>
  <v-container class="text-center" id="contribute">
    <h2 class="display-3 pa-2">Contribute</h2>
    <p
      class="text--secondary mt-4"
    >Veniam ullamco laboris aliquip qui enim in exercitation dolor anim nulla proident irure aliqua consequat.</p>

    <v-container class="grey lighten-5">
      <v-row class="mb-6" justify="space-around" no-gutters>
        <v-col lg="2">
          <v-avatar color="indigo" size="62">
            <v-icon color="white">mdi-account</v-icon>
          </v-avatar>
        </v-col>
        <v-col md="auto">
          <v-card class="pa-2">Variable width content</v-card>
        </v-col>
        <v-col lg="2">
          <v-card class="pa-2">3 of 3</v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {
  name: "Contribute",

  data: () => ({})
};
</script>
