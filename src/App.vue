<template>
  <div id="app">
    <Maze></Maze>
  </div>
</template>

<script>
import Maze from './components/Maze.vue'

export default {
  name: 'app',
  components: {
    Maze
  }
}
</script>

<style>
body {
  margin: 0;
  background-image: url("./assets/background.svg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 100vw;
  /*height: 100vh;*/
}
#app {
  font-family: 'Adrianna', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}
</style>
