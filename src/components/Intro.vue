<template>
<v-container class="d-flex flex-row-reverse mb-6" id="intro">
<v-row >

<v-col class="d-flex flex-col-reverse">
    <v-img
      alt="About"
      class="shrink mr-10"
      contain
      width="300px"
      src="./../assets/aboutApp.svg"
      transition="fab-transition"
    />
    </v-col>
  <v-col>
    
      <p class="font-weight-bold" style="font-size:150px;">
        Abush<span class="font-weight-light" style="font-size:150px;">akir</span>
      </p>
      <div style="margin-top:-30px;">
        <span class="text--secondary" style="font-size:25px;">Sunt eiusmod culpa sint culpa</span>
      </div>

      <v-btn
        class="mt-8"
        round
        color="#03599c"
        width="40%"
        dark
        @click.native.stop="$vuetify.goTo('#about', options)"
      >About</v-btn>
    
</v-col>
    



    </v-row>    
  </v-container>
</template>

<script>
export default {
  name: "About",

  data: () => ({})
};
</script>
