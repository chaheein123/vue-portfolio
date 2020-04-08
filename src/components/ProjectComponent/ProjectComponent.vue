<template src="./ProjectComponent.html"/>

<script>
import ProjectCardComponent from "../ProjectCardComponent/ProjectCardComponent.vue";

export default {
  name: "ProjectComponent",

  components: {
    ProjectCardComponent,
  },

  data: () => ({
    projectCards: [
      { 
        title: "iChat",
        imgUrl: "/project1shot.png",
        webAddress: "http://54.188.94.196:3000/",
        content: "Chat app built with PERN (PostgreSQL, Express.js, React, Node.js) stack.",
        technologies: "PostgreSQL, Express.js, React, Node.js, JSON Web Tokens (JWT), Socket.IO, REST API, Material-UI, Bootstrap, Firebase",
        githubAddress:"https://github.com/chaheein123/chat-app-frontend",
        youtubeAddress:"https://www.youtube.com/watch?v=LfFnA1pO_Zg",
      },
      { 
        title: "iChoose",
        imgUrl: "/project2shot.png",
        webAddress: "https://iichoose.com/",
        content: "What should I eat for lunch? What should I wear? You have a problem choosing? Use this app then!",
        technologies: "Vue.js, Express.js, Node.js, Yelp API, Unsplash.com API, Geolocation API",
        githubAddress: "https://github.com/chaheein123/iChoose-wheel",
        youtubeAddress: "https://www.youtube.com/watch?v=bMgdm3rmqKg",
      },
    ]
  })
}
</script>

<style lang="scss" src="./ProjectComponent.scss" scoped/>