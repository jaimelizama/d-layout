<template>
  <div id="app">
    <NavbarApp></NavbarApp>
    <div class="spacer-block"></div>
    <CharacterCard></CharacterCard>
  </div>
</template>

<script>
import NavbarApp from './components/NavbarApp.vue'
import CharacterCard from './components/CharacterCard.vue'

export default {
  name: 'App',
  components: { CharacterCard, NavbarApp },
  data: () => ({})
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.spacer-block {
  height: 20px;
}
</style>
