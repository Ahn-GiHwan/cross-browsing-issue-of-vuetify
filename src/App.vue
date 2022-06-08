<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-row>
        <v-col class='pink' align='start'>test1</v-col>
        <v-col class='purple' align='center'>test2</v-col>
        <v-col class='orange' align='end'>test2</v-col>
      </v-row>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
