<script setup lang="ts">
</script>

<template>
  <v-container class="rounded-lg pa-0">
    <v-row no-gutters class="text-center">
      <v-col cols="12">
        <v-btn class="w-100 bg-container rounded-lg container-button" height="60" variant="text" href="https://jardsonalan.github.io/portfolio/" target="_blank">
          <v-icon size="30px" icon="fa-solid fa-globe" id="icon-web"/>
          <span class="ml-3">Portfolio</span>
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.bg-container {
  background-color: #141414;
}

.container-button:hover #icon-web {
  transition: .3s;
  color: rgb(0, 140, 255);
  text-shadow: 0 0 3px rgb(0, 140, 255);
}
</style>
