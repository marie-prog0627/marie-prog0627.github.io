<template>
  <v-app>
    <v-app-bar
      app
      color="gray accent-4"
      dark
    >
      <div class="d-flex align-center">
        <v-btn
          href="https://marie-prog0627.github.io"
          target="_blank"
          text
        >
          <span class="mr-2">Ryota Sakuma</span>
        </v-btn>
      </div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content>
      <MyHome/>
    </v-content>
  </v-app>
</template>

<script>
import MyHome from './components/MyHome';

export default {
  name: 'App',

  components: {
    MyHome,
  },

  data: () => ({
    //
  }),
};
</script>
