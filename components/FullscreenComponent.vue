<template>
  <v-container fluid fill-height class="fullscreen-container">
    <v-row wrap align-content="center">
      <v-col cols="12">
        <h1 class="display-4 font-weight-bold">
          Welcome to my website.
        </h1>
        <h3 class="display-1 mt-6">
          My name is MK, and here's a little about myself.
        </h3>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped lang="scss">
.fullscreen-container
{
  min-height:100vh;
  background: linear-gradient( 45deg, #92FFC0 10%, #002661 100%);
  color:#fff;
  text-align:center;
  h1 {
    text-shadow: 0 5px 19px rgba(0,0,0,0.30), 0 4px 6px rgba(0,0,0,0.22);
    font-family:'Product Sans';
  }
  h3 {
    font-family:'Roboto Light';
  }
}
</style>
