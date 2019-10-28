<template>
  <v-layout column style="background: white;">
    <FullscreenComponent />
    <IndexContent />
  </v-layout>
</template>

<script>
import FullscreenComponent from '../components/FullscreenComponent.vue'
import IndexContent from '../components/index/IndexContent.vue'

export default {

  components: {
    FullscreenComponent,
    IndexContent
  }
}
</script>
