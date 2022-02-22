<template>
  <v-app>
    <v-app-bar app>
      <v-tabs
        fixed-tabs
        background-color="#0e1821"
        dark
      >
        <v-tab to="/">
          О нас
        </v-tab>
        <v-tab :to="tabs[1].route" exact>
          Продукция
        </v-tab>
        <v-tab>
          Услуги
        </v-tab>
        <v-tab>
          Документы
        </v-tab>
        <v-tab>
          Контакты
        </v-tab>
        <v-tab-item :value="tabs[0].route">
          <v-container fluid>
            <router-view />
          </v-container>
        </v-tab-item>

        <v-tab-item :value="tabs[1].route">
          <v-container fluid>
            <router-view />
          </v-container>
        </v-tab-item>
      </v-tabs>
    </v-app-bar>

    <!-- Sizes your content based upon application components -->

    <v-footer app>
      <!--  -->
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      activeTab: '/',
      tabs: [
        { route: '/' },
        { route: '/product' }
      ]
    }
  }
}
</script>
