<template>
  <v-app>
    <v-appBar app color="white" dark absolute>
      <div>Hol</div>
    </v-appBar>
    <v-content>
      <v-col align="center" justify="center" class="info--text">
        <router-view />
      </v-col>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "ActividadLayout",
};
</script>
