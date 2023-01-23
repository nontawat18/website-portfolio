<template>
  <div>
    <v-app-bar
      elevation="0"
      height="115"
      color="#ffffff"
      app
      class="pa-1"
    >
      <!-- <v-app-bar-nav-icon></v-app-bar-nav-icon> -->

      <!-- <v-toolbar-title>Page title</v-toolbar-title>-->

      <v-spacer></v-spacer>
      <v-row align="center" >
        <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded to="/"> Home </v-btn>
        </v-col>
        <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded to="/about"> About </v-btn>
        </v-col>
        <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded to="/skills"> Skills </v-btn>
        </v-col>
        <!-- <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded> Services </v-btn>
        </v-col> -->
        <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded to="/portfolio"> Portfolio </v-btn>
        </v-col>
        <v-col class="pb-0" cols="4" sm="4" md="2">
          <v-btn text rounded to="/contact"> Contact </v-btn>
        </v-col>
      </v-row>
      <v-spacer></v-spacer>
    </v-app-bar>
  </div>
</template>
