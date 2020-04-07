<template src="./ProjectCardComponent.html"/>

<script>
export default {
  name: "ProjectCardComponent",

  props: ["cardInfo"],

  data: () => ({
    show: false,
  }),
}
</script>

<style lang="scss" src="./ProjectCardComponent.scss" scoped/>