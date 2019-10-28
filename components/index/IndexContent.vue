<template>
  <v-container>
    <v-row wrap justify="center">
      <v-col cols="6" class="my-4" style="text-align:center">
        <MyPhoto />
      </v-col>
      <v-col cols="12">
        <p class="headline text-center">
          My name is Matthew Kevin Amadeus, commonly abbreviated as MK. I’m a student who is eager to learn in the fields and branches of computer science. I look forward upon cooperating with you!
        </p>
      </v-col>
      <v-col cols="6">
        <InfoCardComponent />
      </v-col>
      <v-col cols="6">
        abcdef
      </v-col>
      <v-col cols="6">
        abcdef
      </v-col>
      <v-col cols="6">
        abcdef
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import MyPhoto from './MyPhoto.vue'
import InfoCardComponent from './InfoCardComponent'

export default {
  components: {
    MyPhoto,
    InfoCardComponent
  }
}
</script>
