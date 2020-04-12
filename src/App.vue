<template>
  <v-app>
<Toolbar/>
    <v-content>
      <Home/>
    </v-content>
  </v-app>
</template>

<script>

import Home from './components/Home';
import Toolbar from './components/Toolbar';

export default {
  name: 'App',

  components: {
    Home,
Toolbar
  },

  data: () => ({
    //
  }),
};
</script>
