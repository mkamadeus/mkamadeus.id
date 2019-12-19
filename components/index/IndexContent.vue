<template>
  <v-container>
    <v-row wrap justify="center" align="center">
      <v-col cols="12" class="my-4" align="center">
        <MyPhoto />
      </v-col>
      <v-col cols="12" class="title text-center px-4">
        My name is Matthew Kevin Amadeus, commonly abbreviated as MK. I’m a student who is eager to learn in the fields and branches of computer science and software engineering. I look forward upon cooperating with you!
      </v-col>
      <v-col cols="10" sm="6" md="4">
        <v-responsive aspect-ratio="1" class="pa-2">
          <InfoCardComponent
            :info-title="'Biodata'"
            :icon-name="'mdi-account'"
            :info-text="'Born in Jakarta, grew up in Gading Serpong, and currently living in Bandung.'"
          />
        </v-responsive>
      </v-col>
      <v-col cols="10" sm="6" md="4">
        <v-responsive aspect-ratio="1" class="pa-2">
          <InfoCardComponent
            :info-title="'Education'"
            :icon-name="'fa-graduation-cap'"
            :icon-color="'yellow darken-2'"
            :info-text="'Currently studying in Institut Teknologi Bandung as a Informatics Undergraduate.'"
          />
        </v-responsive>
      </v-col>
      <v-col cols="10" sm="6" md="4">
        <v-responsive aspect-ratio="1" class="pa-2">
          <InfoCardComponent
            :info-title="'Interest'"
            :icon-name="'fa-code'"
            :icon-color="'red darken-1'"
            :info-text="'Have been interested in programming since middle school; continuing to develop new skills.'"
          />
        </v-responsive>
      </v-col>
      <!-- <v-col cols="10" sm="6" md="4">
        abcdef
      </v-col> -->
    </v-row>
  </v-container>
</template>

<style lang="scss" scoped>

</style>

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
