<template>
  <v-footer
    dark
    height="auto"
  >
    <v-card
      class="flex"
      flat
      tile
    >
      <v-card-title class="teal">
        <strong class="subheading">Connect met mij!</strong>

        <v-spacer></v-spacer>
          <v-flex xs2> <a href="https://github.com/Sweetpurple616">
          <v-icon dark icon size="24px">fa-github</v-icon> </a> </v-flex>
          <v-flex xs2> <a href="https://www.linkedin.com/in/zo%C3%AB-de-waard-973b22108/">
          <v-icon dark icon size="24px">fa-linkedin</v-icon> </a> </v-flex> 
      </v-card-title>

      <v-card-actions class="grey darken-3 justify-center">
        <div>&copy; {{ new Date().getFullYear() }}— <strong>Zoë de Waard</strong> </div>
      </v-card-actions>
    </v-card>
  </v-footer>
</template>
<script>
export default {

}
</script>

<style>

</style>
