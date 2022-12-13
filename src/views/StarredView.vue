<script setup lang="ts">
import FrameworkPop from "@/components/FrameworkPop.vue";
const frameList = [
  {
    name: "VueJS",
    img: "https://img.icons8.com/color/512/vue-js.png",
    rating: 10,
  },
  {
    name: "AngularJS",
    img: "https://material.angularjs.org/latest/img/logo.svg",
    rating: 20,
  },
  {
    name: "ReatJS",
    img: "https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png",
    rating: 14,
  },
];
function changeRating(index: number, rating: number) {
  console.log("action" + index + " :" + rating);
}
</script>

<template>
  <v-container>
    <v-row>
      <v-col v-for="(item, index) of frameList" :key="index">
        <FrameworkPop
          :name="item.name"
          :img="item.img"
          :rating="item.rating"
          :index="index"
          @change="changeRating"
        ></FrameworkPop>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-table>
          <thead>
            <tr>
              <th>order</th>
              <th>name</th>
              <th>rating</th>
            </tr>
          </thead>
          <tbody>
            <tr v-for="(item, index) of frameList" :key="index">
              <td>{{ index + 1 }}</td>
              <td>{{ item.name }}</td>
            </tr>
          </tbody>
        </v-table>
      </v-col>
    </v-row>
  </v-container>
</template>
