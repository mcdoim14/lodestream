<template>
  <LandingPage>
    <TwitchPlayer></TwitchPlayer>
  </LandingPage>
</template>

<script>
import LandingPage from './components/LandingPage.vue'
import TwitchPlayer from './components/TwitchPlayer.vue';

Vue.use(LoadScript);

export default {
  name: 'App',
  components: {
    LandingPage,
    TwitchPlayer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

</style>
