<template src="./MainPage.html"/>

<script>
import TopComponent from "../../components/TopComponent/TopComponent.vue";
import NavComponent from "../../components/NavComponent/NavComponent.vue";
import AboutComponent from "../../components/AboutComponent/AboutComponent.vue";
import ProjectComponent from "../../components/ProjectComponent/ProjectComponent.vue";
import ContactComponent from "../../components/ContactComponent/ContactComponent.vue";

export default {
  name: "MainPage",

  components: {
    TopComponent,
    NavComponent,
    AboutComponent,
    ProjectComponent,
    ContactComponent,
  },

  data: () => ({
    
  })
};
</script>

<style lang="scss" scoped src="./MainPage.scss" />