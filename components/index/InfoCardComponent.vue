<template>
  <v-card raised rounded height="100%" class="pa-5">
    <v-row class="justify-center card-contents">
      <v-list-item>
        <v-list-item-content>
          <v-icon size="100" :color="iconColor">
            {{ iconName }}
          </v-icon>
          <div class="display-2 font-weight-bold text-center">
            {{ infoTitle }}
          </div>
        </v-list-item-content>
      </v-list-item>
      <v-list-item>
        <v-list-item-content class="text-center">
          {{ infoText }}
        </v-list-item-content>
      </v-list-item>
    </v-row>
  </v-card>
</template>

<style scoped lang="scss">
.card-contents {
  height:100%;
}
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
    'iconColor': {
      default: 'blue darken-2',
      type: String
    },
    'iconName': {
      default: '',
      type: String
    }
  }
}
</script>
