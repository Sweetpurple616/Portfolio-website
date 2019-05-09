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
        <strong class="subheading">Get connected with us on social networks!</strong>

        <v-spacer></v-spacer>

          <v-icon dark icon size="24px">fa-github</v-icon>
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
