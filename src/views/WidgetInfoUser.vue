<script setup lang="ts">
</script>

<template>
  <v-container class="bg-black rounded-lg">
    <v-row>
      <v-col cols="3">
        <!-- Imagem de perfil -->
        <v-img
          src="/profile-image.jpg"
          class="rounded-lg"
          :width="300"
          cover
        />
      </v-col>
      <v-col cols="9" class="d-flex flex-column justify-center">
        <!-- Nome e Stack -->
        <span class="text-subtitle-2 font-weight-bold">Jardson Alan</span>
        <span class="text-caption">Desenvolvedor de Software</span>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
</style>
