<template src="./NavComponent.html"/>

<script>
export default {
  name: "NavComponent",

  data: () => ({
    items: [
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me 2' },
    ],
    hamburgerClicked:false
  }),
}
</script>

<style lang="scss" scoped src="./NavComponent.scss"/>