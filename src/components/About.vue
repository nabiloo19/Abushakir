<template>
  <v-container class="text-center"  id="about">

    <v-container fluid>
      <v-card class="elevation-12 pa-12">
      <span class="display-3">About</span>
      <p class="mt-5">Incididunt velit labore dolore do occaecat mollit sunt pariatur quis dolore veniam reprehenderit ut cillum.</p>
      <v-row dense>
        <v-col
          v-for="card in cards"
          :key="card.title"
          :cols="card.flex"
        >
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="200px"
            >
              <v-card-title v-text="card.title"></v-card-title>
            </v-img>

            
        </v-col>
      </v-row>
          </v-card>
    </v-container>
  

  </v-container>
</template>

<script>
  export default {
    name: 'About',

    data: () => ({
    cards: [
        
        { title: 'Performance', src: './../assets/logo.png', flex: 4 },
        { title: 'Well-Documented', src: '@/../../assets/aboutApp.svg', flex: 4 },
        { title: 'Robust', src: '@/../../assets/aboutApp.svg', flex: 4 },
      ],
    }),
  }
</script>
