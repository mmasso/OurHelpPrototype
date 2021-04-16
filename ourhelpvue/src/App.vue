<template>
  <v-app>
    <Menu/>
  </v-app>
</template>

<script>

import Menu from "./components/menu"

export default {
  name: 'App',

  components: {
    Menu
  },

  data: () => ({
    //
  }),
};
</script>

<style>
  .v-window-item { 
    color: black}
  .v-sheet.v-card {
    /* border-radius: 4px; */
    border-radius: 0px !important;
  }
  .v-application{

    }
</style>