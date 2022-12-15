<template>
  <v-app :theme="theme">
    <v-app-bar>
      <v-spacer></v-spacer>

      <v-btn
        :prepend-icon="theme === 'light' ? mdiWeatherSunny : mdiWeatherNight"
        @click="onClick"
        >Toggle Theme</v-btn
      >
    </v-app-bar>
    <v-navigation-drawer expand-on-hover rail permanent>
      <v-list>
        <v-list-item
          prepend-avatar="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
          title="Thitiphong Nimmak"
          subtitle="64160048@go.buu.ac.th"
        ></v-list-item>
      </v-list>

      <v-divider></v-divider>

      <v-list density="compact" nav>
        <v-list-item
          :prepend-icon="mdiFolder"
          title="My Files"
          value="myfiles"
          to="/my-files-view"
        ></v-list-item>
        <v-list-item
          :prepend-icon="mdiAccountMultiple"
          title="My Profile"
          value="Myprofile"
          to="/my-profile"
        ></v-list-item>
        <v-list-item
          :prepend-icon="mdiStar"
          title="Starred"
          value="starred"
          to="/starred"
        ></v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import { ref } from "vue";
import {
  mdiStar,
  mdiAccountMultiple,
  mdiFolder,
  mdiWeatherSunny,
  mdiWeatherNight,
  mdiCursorPointer,
  mdiVuetify,
  mdiCheckboxMarkedCircle,
} from "@mdi/js";
const theme = ref("light");

function onClick() {
  theme.value = theme.value === "light" ? "dark" : "light";
}
</script>
