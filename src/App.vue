<template>
  <div id="app">
    <div style="float: left;">
      <img src="../img/profile_pic.jpg" />
    </div>
    <div style="float: right;">
      Hello
    </div>

    <!--
    linkedin
    github
    resume blurbs
    work history
    contact information
    <Main msg="Welcome to Peter's Website"/>
    -->
  </div>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'app',
  components: {
    Main
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: -10px;
  height: 100vh;
}
</style>
