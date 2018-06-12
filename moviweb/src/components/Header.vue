<template>
   <v-app >
    <v-toolbar class="blue" hide-overlay>
      <v-toolbar-title>MW</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn flat>World</v-btn>
        <v-btn flat>India</v-btn>
        <v-btn flat>Movie</v-btn>
        <v-btn flat>Politics</v-btn>
        <v-btn flat>Sports</v-btn>
        <v-btn flat>Business</v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </v-app>
</template>

<script>
export default {
  data() {
      return {
         sideNav: false
  }
}
}
</script>

<style>

</style>
