<script setup lang="ts">
import FancyButton from "@/components/FancyButton.vue";
import { mdiHeartOutline, mdiCursorDefaultClickOutline } from "@mdi/js";
</script>

<template>
  <v-container>
    <v-row>
      <v-col
        ><FancyButton
          ><v-icon :icon="mdiHeartOutline" /> Love Me
          <template v-slot:tail> Tail </template>
        </FancyButton>
      </v-col>
      <v-col
        ><FancyButton
          ><v-icon :icon="mdiCursorDefaultClickOutline" /> Click Me
          <template #tail> My Tail </template>
        </FancyButton>
      </v-col>
    </v-row>
  </v-container>
</template>
