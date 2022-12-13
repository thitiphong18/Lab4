<script setup lang="ts">
import FancyButton from "@/components/FancyButton.vue";
import { mdiHeartOutline } from "@mdi/js";
</script>

<template>
  <v-container>
    <v-row>
      <v-col
        ><FancyButton><v-icon :icon="mdiHeartOutline" /> Click Me</FancyButton>
      </v-col>
    </v-row>
  </v-container>
</template>
