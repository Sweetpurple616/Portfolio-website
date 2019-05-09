<template>
<div id="gifDiv">
  <v-parallax
  height="700"
    :src="require('@/assets/GifofMe.gif')"
    contain

  >
    <v-layout
      align-center
      column
      justify-center
    >
      <h1 class="display-2 font-weight-thin mb-3">Zoë de Waard</h1>
      <h4 class="subheading">Creative Technoloog</h4>
    </v-layout>
    
  </v-parallax>
</div>
</template>

<script>
export default {

}
</script>

<style>
#gifDiv img {
  height: 1000
}
</style>
