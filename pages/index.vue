<template>
  <v-flex style="background: white;">
    <FullscreenComponent />
    <IndexContent />
    <Footer />
  </v-flex>
</template>

<script>
import FullscreenComponent from '../components/FullscreenComponent.vue'
import IndexContent from '../components/index/IndexContent.vue'
import Footer from '../components/partials/Footer.vue'

export default {

  components: {
    FullscreenComponent,
    IndexContent,
    Footer
  }
}
</script>
