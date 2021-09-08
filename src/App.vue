<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <router-view />
</template>

<script setup>
import { useLink } from "vue-router";

//  uncomment line below to break the application
// const { route } = useLink();
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
