<template>
  <div id="app">
    <ilPrimissimo/>
    <bannerHero/>
  </div>
</template>

<script>
import ilPrimissimo from './components/ilPrimissimo.vue'
import bannerHero from './components/bannerHero.vue'

export default {
  name: 'App',
  components: {
    ilPrimissimo,
    bannerHero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
