<script setup lang="ts">
</script>

<template>
  <v-container class="bg-container rounded-lg">
    <v-row>
      <v-col cols="3">
        <!-- Imagem de perfil -->
        <v-img
          src="profile-image.jpg"
          class="rounded-lg image-profile"
          :width="300"
          cover
        />
      </v-col>
      <v-col cols="9" class="d-flex flex-column justify-center">
        <!-- Nome e Stack -->
        <span class="text-h6 font-weight-bold">Jardson Alan</span>
        <span class="text-subtitle-2">Desenvolvedor de Software</span>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.bg-container {
  background-color: #141414;
}

.image-profile {
  border: 2px solid rgb(42, 42, 240);
  box-shadow: 0 0 10px rgb(34, 34, 253);
}
</style>
