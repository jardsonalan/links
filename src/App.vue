<script setup lang="ts">
import WidgetInfoUser from './views/WidgetInfoUser.vue';
</script>

<template>
  <v-responsive>
    <v-app class="bg-black">
      <v-container class="w-100 bg-grey-darken-4 mt-8 rounded-lg" max-width="320" min-height="400">
        <WidgetInfoUser/>
      </v-container>
    </v-app>
  </v-responsive>
</template>

<style scoped>
</style>
