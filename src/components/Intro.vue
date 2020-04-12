<template>
  <v-container class="text-center d-flex  flex-row-reverse mb-6"  id="intro">
    <v-flex class="pr-5">
    <p class="font-weight-bold" style="font-size:150px;">Abush<span class="font-weight-light" style="font-size:150px;">akir</span>
    </p> 
    <div style="margin-top:-50px;">
    <span class="text--secondary" style="font-size:25px;">Sunt eiusmod culpa sint culpa</span>
    </div>

    <v-btn class="mt-4" round color="#03599c" width="40%" dark @click.native.stop="$vuetify.goTo('#about', options)">About</v-btn>
    </v-flex>

    <!-- <v-flex > -->
      <v-img
            alt="About"
            class="shrink mr-10"
            contain
            width="300px"
            
            src="./../assets/aboutApp.svg"
            transition="scale-transition"
            
          />
    <!-- </v-flex> -->
  </v-container>
</template>

<script>
  export default {
    name: 'About',

    data: () => ({
    
    }),
  }
</script>
