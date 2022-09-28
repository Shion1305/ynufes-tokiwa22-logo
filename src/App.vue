<template>
  <div id="wrapper">
    なかみなかみ
    <!--    <div id="loader">-->
    <!--      <LogoAnimation id="logo-animation"/>-->
    <!--      <div id="logo-text">横浜国立大学<br>2022年常盤祭</div>-->
    <!--      <div id="logo-date">10/28,29,30</div>-->
    <!--    </div>-->
  </div>
</template>

<script>
window.onload = function () {
  const loader = document.getElementById('loader');
  loader.classList.add('loaded');
}
</script>

<style>
#wrapper {
  display: flex;
  flex-direction: column;
}

body {
  margin: 0;
  height: 100%;
  background: #051228;
  color: white;
}
#app {
  font-family: 'Klee One', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
