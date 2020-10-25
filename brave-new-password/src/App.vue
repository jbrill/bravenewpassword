<template>
  <v-app>
    <v-app-bar
      app
      color="rgb(22, 36, 67)"
      dark
    >
      <div class="d-flex align-center">
        <span class="headline">BRAVE NEW PASSWORD</span>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/jbrill/bravenewpassword"
        target="_blank"
        text
      >
        <span class="mr-2">Code</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <GeneratePasswordCard/>
    </v-main>
  </v-app>
</template>

<script>
import GeneratePasswordCard from './components/GeneratePasswordCard';

export default {
  name: 'App',

  components: {
    GeneratePasswordCard,
  },

  data: () => ({
    //
  }),
};
</script>
