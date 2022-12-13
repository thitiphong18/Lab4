<script setup lang="ts">
import FrameworkPop from "@/components/FrameworkPop.vue";
</script>

<template>
  <v-container>
    <v-row>
      <v-col>
        <FrameworkPop
          name="VueJS"
          img="https://img.icons8.com/color/512/vue-js.png"
          :rating="10"
        ></FrameworkPop>
      </v-col>
    </v-row>
  </v-container>
</template>
