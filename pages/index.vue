<template>
  <v-container fluid style="background: white;" class="pa-0">
    <FullscreenComponent />
    <IndexContent />
  </v-container>
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
