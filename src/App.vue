<template>
  <v-app>
    <v-main>
      <v-app-bar color="#081444" elevation="4">
        <v-container>
          <h2 class="topText">Prueba Front End</h2>
          <v-spacer> </v-spacer>
        </v-container>
        <a
          href="https://github.com/mquintero0118/envia/tree/master"
          target="_blank"
          class="topText"
          >Repositorio Git</a
        >
      </v-app-bar>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
<style scoped>
.topText {
  color: white;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
</style>
