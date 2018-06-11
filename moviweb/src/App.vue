<template>
   <v-app dark>
     <v-navigation-drawer fixed v-model="sideNav">
       <v-list>
         <v-list-tile>
           <v-list-tile-content>World</v-list-tile-content>
           <v-list-tile-content>World</v-list-tile-content>
           <v-list-tile-content>World</v-list-tile-content>
         </v-list-tile>
       </v-list>
      </v-navigation-drawer>
    <v-toolbar hide-overlay>
      <v-toolbar-side-icon @click.native.stop="sideNav!=sideNav"></v-toolbar-side-icon>
      <v-toolbar-title>MW</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only">
        <v-btn flat>World</v-btn>
        <v-btn flat>India</v-btn>
        <v-btn flat>Movie</v-btn>
        <v-btn flat>Politics</v-btn>
        <v-btn flat>Sports</v-btn>
        <v-btn flat>Business</v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <main>

    </main>
  </v-app>
</template>

<script>
export default {
  data() {
      return {
         sideNav: false ,
  }
}
}
</script>

<style>

</style>
