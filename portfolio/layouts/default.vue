<template>
  <v-app dark>
    <Navbar />
    <v-main id="scrolling-techniques-7" class="overflow-y-auto">
      <v-col>
        <!-- <v-container> -->
        <Nuxt />
        <!-- </v-container> -->
      </v-col>
    </v-main>

    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/",
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire",
        },
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Portfolio",
    };
  },
};
</script>
