<template>
  <div id="wrapper">
    <div id="loader">
      <LogoAnimation id="logo-animation"/>
      <div id="logo-text">横浜国立大学<br>2022年常盤祭</div>
      <div id="logo-date">10/28,29,30</div>
    </div>
  </div>
</template>

<script>
import LogoAnimation from './components/LogoAnimation.vue'

export default {
  name: 'App',
  components: {
    LogoAnimation
  }
}
</script>

<style>
body {
  margin: 0;
  height: 100%;
  background: #051228;
  color: white;
}

#logo-animation {
  width: min(65vw, 350px);
}

#logo-date {
  font-size: 1.5em;
}

#logo-text {
  font-size: min(8vw, 2em);
}

#app {
  font-family: 'Klee One', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
