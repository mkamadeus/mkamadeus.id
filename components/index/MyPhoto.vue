<template>
  <v-img :src="require('~/assets/self_photo.jpg')" contain aspect-ratio="1" width="250" class="my-photo" />
</template>

<style lang="scss" scoped>
.my-photo {
  box-shadow: 0 5px 19px rgba(0,0,0,0.30), 0 4px 6px rgba(0,0,0,0.22);
  width:50%;
  max-width:100%;
  border-radius: 50%;
  text-align:center;
}
</style>
