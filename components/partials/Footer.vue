<template>
  <v-container fluid class="pa-0">
    <v-row class="footer-container" no-gutters>
      <v-col cols="12" class="pa-0 px-6">
        <v-row align="center" justify="center" class=" fill-height footer">
          <v-col cols="6">
            <div :class="($vuetify.breakpoint.lgAndDown?'headline':'display-1')+' pa-2'">
              Connect with me.
            </div>
          </v-col>
          <v-col cols="6" class="pa-0" style="height:100%;">
            <v-container class="fill-height pa-0">
              <v-row wrap align="center" justify="center" class="fill-height">
                <v-col v-for="i in 4" :key="i" cols="3" :style="style[i-1]" class="fill-height">
                  <v-row align="center" class="fill-height">
                    <v-col class="pa-0">
                      <v-icon :size="$vuetify.breakpoint.lgAndDown?30:60" color="#fff">
                        {{ iconNames[i-1] }}
                      </v-icon>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>
            </v-container>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style lang="scss" scoped>
.footer-container {
  width: 100vw;
  min-height: 15vh;
  background-color:#111;
}
.footer {
  color: #fff;
  text-align: center;
}
</style>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'Footer',
  data () {
    return {
      iconNames: ['mdi-github-circle', 'fab fa-line', 'mdi-instagram', 'mdi-dribbble'],
      style: [{ backgroundColor: '#000000' }, { backgroundColor: '#42c507' }, { backgroundColor: '#7d32aa' }, { backgroundColor: '#d62977' }]
    }
  }
})
</script>
