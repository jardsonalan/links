<script setup lang="ts">
import WidgetInfoUser from './views/WidgetInfoUser.vue';
import WidgetHardSkills from './views/WidgetHardSkills.vue';
import WidgetSocialMedia from './views/WidgetSocialMedia.vue';
import WidgetSite from './views/WidgetSite.vue';
import WidgetGitHub from './views/WidgetGitHub.vue';
</script>

<template>
  <v-responsive>
    <v-app class="bg-black">
      <v-container class="w-100 bg-black mt-8 rounded-lg container">
        <v-row>
          <v-col cols="12">
            <WidgetInfoUser/>
          </v-col>
          <v-col cols="12">
            <WidgetHardSkills/>
          </v-col>
          <v-col cols="7">
            <WidgetGitHub/>
          </v-col>
          <v-col cols="5" class="pa-0">
            <WidgetSocialMedia/>
          </v-col>
          <v-col cols="12">
            <WidgetSite/>
          </v-col>
        </v-row>
      </v-container>
    </v-app>
  </v-responsive>
</template>

<style scoped>
.container {
  width: 80%;
  max-width: 400px;
}
</style>
