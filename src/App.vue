<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Timeline msg="Teamwork Task Timeline"/>
  </div>
</template>

<script>
import Timeline from './components/Timeline.vue'

export default {
  name: 'app',
  components: {
    Timeline
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
