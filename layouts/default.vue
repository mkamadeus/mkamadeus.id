<template>
  <v-app style="background: white">
    <v-content class="pa-0">
      <nuxt />
    </v-content>
    <v-footer padless>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
import Vue from 'vue'
import Footer from '../components/partials/Footer.vue'

export default Vue.extend({
  components: {
    Footer
  }
})
</script>
