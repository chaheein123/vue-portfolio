<template>
  <v-app>
    <MainPage />
  </v-app>
</template>

<script>
import MainPage from "./pages/MainPage/MainPage";

export default {
  name: "App",

  components: {
    MainPage
  },

  data: () => ({
    //
  })
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

a {
  text-decoration: none;
}
</style>
