<template>
  <div id="app">
    <WelcomeComponent msg="Welcome"></WelcomeComponent>
    <NavbarComponent msg="Welcome"></NavbarComponent>
    <LandingComponent msg="Welcome"></LandingComponent>
  </div>
  
</template>

<script>
import WelcomeComponent from './components/WelcomeComponent.vue'
// import NavbarComponent from './components/NavbarComponent.vue'
import LandingComponent from './components/LandingComponent.vue'

export default {
  name: "App",
  components: {
    WelcomeComponent,
    // NavbarComponent,
    LandingComponent
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
  background-color: black;
}
</style>
