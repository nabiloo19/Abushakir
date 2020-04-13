<template>
  <v-container class="mt-8 mb-6" id="competition">
    <h2 class="display-2 mt-2 text-center">Competition</h2>
    <p
      class="text-center pt-3 text--secondary"
    >Ullamco sint Lorem Lorem Lorem proident irure officia commodo amet esse.</p>

    <v-flex>
      <v-row no-gutters class="pa-12">
        <v-col cols="6">
          <v-img
            alt="About"
            class="shrink ml-10"
            contain
            width="300px"
            src="./../assets/aboutApp.svg"
            transition="fab-transition"
          />
        </v-col>

        <v-col class="ma-5">
          <h2 class="display-3">Build a project</h2>
          <h3 class="text--secondary mt-6">Enim sit ipsum in labore duis proident ut.</h3>
        </v-col>
      </v-row>
    </v-flex>

    <v-flex class="mt-12">
      <v-row no-gutters class="pa-12">
        <v-col class="ma-5">
          <h2 class="display-3">Create Apps</h2>
          <h3 class="text--secondary mt-6">Enim sit ipsum in labore duis proident ut.</h3>
        </v-col>
        <v-col cols="6">
          <v-img
            alt="About"
            class="shrink ml-10"
            contain
            width="300px"
            src="./../assets/aboutApp.svg"
            transition="fab-transition"
          />
        </v-col>
      </v-row>
    </v-flex>
    <v-flex class="mt-12">
      <v-row no-gutters class="pa-12">
        <v-col cols="6">
          <v-img
            alt="About"
            class="shrink ml-10"
            contain
            width="300px"
            src="./../assets/aboutApp.svg"
            transition="fab-transition"
          />
        </v-col>
        <v-col class="ma-5">
          <h2 class="display-3">Get Recognition</h2>
          <h3 class="text--secondary mt-6">Enim sit ipsum in labore duis proident ut.</h3>
        </v-col>
      </v-row>
    </v-flex>

    <v-card
      dark
      style="margin-left:25%;"
      class="text-center elevation-10"
      color="#03599c"
      width="50%"
      height="150px"
    >
      <h2 class="display-2 pt-5">How To Compete</h2>
      <p style="opacity:0.8" class="pt-3" dark>Esse reprehenderit eu officia ad.</p>
    </v-card>
    <v-card class="elevation-10">
      <v-simple-table>
        <template v-slot:default>
          <thead>
            <tr>
              <th class="text-left headline">
                <v-icon color="#03599c" class="mr-2">mdi-lightbulb-on-outline</v-icon>Ideas
              </th>

              <th class="text-left headline">
                <v-icon color="#03599c" class="mr-2">mdi-desktop-mac</v-icon>Desktop
              </th>

              <th class="text-left headline">
                <v-icon color="#03599c" class="mr-2">mdi-code-tags</v-icon>Web
              </th>

              <th class="text-left headline">
                <v-icon color="#03599c" class="mr-2">mdi-cellphone</v-icon>Mobile
              </th>
            </tr>
          </thead>
          <tbody>
            <tr v-for="item in desserts" :key="item.name">
              <td>{{ item.name }}</td>
              <td>{{ item.calories }}</td>
              <td>{{ item.calories }}</td>
              <td>{{ item.calories }}</td>
            </tr>
          </tbody>
        </template>
      </v-simple-table>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "Competition",

  data: () => ({
    desserts: [
      {
        name: "Frozen Yogurt",
        calories: 159
      },
      {
        name: "Ice cream sandwich",
        calories: 237
      },
      {
        name: "Eclair",
        calories: 262
      },
      {
        name: "Cupcake",
        calories: 305
      },
      {
        name: "Gingerbread",
        calories: 356
      },
      {
        name: "Jelly bean",
        calories: 375
      },
      {
        name: "Lollipop",
        calories: 392
      },
      {
        name: "Honeycomb",
        calories: 408
      },
      {
        name: "Donut",
        calories: 452
      },
      {
        name: "KitKat",
        calories: 518
      }
    ]
  })
};
</script>
