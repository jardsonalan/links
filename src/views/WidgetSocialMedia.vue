<script setup lang="ts">
</script>

<template>
  <v-container class="rounded-lg pa-0 mt-3 ml-n1">
    <v-row no-gutters class="text-center">
      <v-col cols="6">
        <v-btn class="bg-black mb-2 rounded-lg container-button" height="50">
          <v-icon size="30" icon="fa-brands fa-tiktok" id="icon-tiktok"/>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <v-btn class="bg-black rounded-lg container-button" height="50">
          <v-icon size="30" icon="fa-brands fa-instagram" id="icon-instagram"/>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <v-btn class="bg-black rounded-lg container-button" height="50">
          <v-icon size="30" icon="fa-brands fa-youtube" id="icon-youtube"/>
        </v-btn>
      </v-col>
      <v-col cols="6">
        <v-btn class="bg-black rounded-lg container-button" height="50">
          <v-icon size="30" icon="fa-brands fa-linkedin" id="icon-linkedin"/>
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.container-button:hover #icon-tiktok {
  color: rgb(174, 0, 255);
  transition: .3s;
}

.container-button:hover #icon-instagram {
  color: rgb(255, 0, 119);
  transition: .3s;
}

.container-button:hover #icon-youtube {
  color: rgb(255, 0, 21);
  transition: .3s;
}

.container-button:hover #icon-linkedin {
  color: rgb(0, 68, 255);
  transition: .3s;
}
</style>
