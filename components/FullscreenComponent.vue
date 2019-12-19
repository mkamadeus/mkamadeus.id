<template>
  <v-row fluid align="center" justify="center" class="fullscreen-container">
    <v-col cols="12">
      <v-row class="text-container" align="center" justify="center">
        <v-col cols="10">
          <h1 v-show="$vuetify.breakpoint.lgAndDown" class="display-2 font-weight-bold">
            Welcome to my website.
          </h1>
          <h1 v-show="$vuetify.breakpoint.lgAndUp" class="display-4 font-weight-bold">
            Welcome to my website.
          </h1>
          <h3 v-show="$vuetify.breakpoint.lgAndDown" class="headline">
            My name is MK, and here's a little about myself.
          </h3>
          <h3 v-show="$vuetify.breakpoint.lgAndUp" class="display-1">
            My name is MK, and here's a little about myself.
          </h3>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>

<style scoped lang="scss">
.fullscreen-container{
  height:100vh;
  background: linear-gradient( 45deg, #92FFC0 10%, #002661 100%);
  .text-container {
    color:#fff;
    text-align: center;
    h1 {
      text-shadow: 0 5px 19px rgba(0,0,0,0.30), 0 4px 6px rgba(0,0,0,0.22);
      position: relative;
      bottom:20px;
    }
    h3 {
      position: relative;
      top: 20px;
    }
  }
}
</style>
