<template>
  <div class="footer-container">
    <v-container class="footer">
      <v-row>
        <v-col cols="6">
          <div class="display-2">
            Connect with me.
          </div>
        </v-col>
        <v-col cols="6">
          <v-icon size="80" color="#fff">
            mdi-github-circle
          </v-icon>
          <v-icon size="80" color="#fff">
            mdi-instagram
          </v-icon>
          <v-icon size="80" color="#fff">
            mdi-dribbble
          </v-icon>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style lang="scss" scoped>
.footer-container {
  width: 100vw;
  background-color:#000;
}
.footer {
  color: #fff;
}
</style>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'Footer'
})
</script>
