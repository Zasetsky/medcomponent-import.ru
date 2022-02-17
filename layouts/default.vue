<template>
  <v-app>
    <v-app-bar app>
      <v-tabs
        fixed-tabs
        background-color="indigo"
        dark
      >
        <v-tab>
          Option
        </v-tab>
        <v-tab>
          Another Selection
        </v-tab>
        <v-tab>
          Items
        </v-tab>
        <v-tab>
          Another Screen
        </v-tab>
      </v-tabs>
    </v-app-bar>

    <!-- Sizes your content based upon application components -->
    <v-main>
      <v-container fluid>
        <Nuxt />
      </v-container>
    </v-main>

    <v-footer app>
      <!-- -->
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
