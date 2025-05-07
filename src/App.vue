<script setup lang="ts">
import WidgetInfoUser from './views/WidgetInfoUser.vue';
import WidgetHardSkills from './views/WidgetHardSkills.vue';
import WidgetSocialMedia from './views/WidgetSocialMedia.vue';
// import WidgetSite from './views/WidgetSite.vue';
import WidgetGitHub from './views/WidgetGitHub.vue';
</script>

<template>
  <v-responsive>
    <v-app class="bg-black">
      <v-container class="w-100 bg-grey-darken-4 mt-8 rounded-lg" max-width="320" min-height="400">
        <v-row>
          <v-col cols="12">
            <WidgetInfoUser/>
          </v-col>
          <v-col cols="12">
            <WidgetHardSkills/>
          </v-col>
          <v-col cols="6">
            <!-- <WidgetSite/> -->
            <WidgetGitHub/>
          </v-col>
          <v-col cols="6" class="pa-0">
            <WidgetSocialMedia/>
          </v-col>
        </v-row>
      </v-container>
    </v-app>
  </v-responsive>
</template>

<style scoped>
</style>
