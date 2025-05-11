<script setup lang="ts">
</script>

<template>
  <v-container class="rounded-lg pa-0">
    <v-row no-gutters class="text-center">
      <v-col cols="12">
        <v-btn class="w-100 bg-container rounded-lg container-button" height="129px" variant="text" href="https://github.com/jardsonalan" target="_blank">
          <v-icon size="60px" icon="mdi:mdi-github" id="icon-web"/>
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.bg-container {
  background-color: #0c0c0c;
}

.container-button:hover #icon-web {
  transition: .3s;
  text-shadow: 0 0 3px white;
}
</style>
