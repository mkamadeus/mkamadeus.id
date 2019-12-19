<template>
  <v-card raised rounded class="pa-5" height="100%">
    <v-list-item>
      <v-list-item-content>
        <v-icon size="100" color="blue darken-2">
          {{ iconName }}
        </v-icon>
        <div class="display-1 font-weight-bold text-center">
          {{ infoTitle }}
        </div>
      </v-list-item-content>
    </v-list-item>
    <v-list-item>
      <v-list-item-content class="text-center">
        {{ infoText }}
      </v-list-item-content>
    </v-list-item>
  </v-card>
</template>

<style scoped lang="scss">
</style>

<script>
export default {
  props: {
    'infoText': {
      default: '',
      type: String
    },
    'infoTitle': {
      default: '',
      type: String
    },
    'iconName': {
      default: '',
      type: String
    }
  }
}
</script>
