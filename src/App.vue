<template>
  <LogoAnimation msg="Welcome to Your Vue.js App"/>
  <SvgTest/>
</template>

<script>
import LogoAnimation from './components/LogoAnimation.vue'
import SvgTest from "@/components/SvgTest";

export default {
  name: 'App',
  components: {
    SvgTest,
    LogoAnimation
  }
}
</script>

<style>
body {
  margin: 0;
  background: black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
