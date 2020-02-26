<template>
  <v-app dark>
    <v-content>
      <router-view />
    </v-content>
    <v-footer :fixed="fixed" app>
      <span>&nbsp;&copy; 2018-2020</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [
        {
          icon: "bubble_chart",
          title: "Inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
