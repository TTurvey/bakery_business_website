<template>
  <div id="app">
    <HomeComponent msg="Welcome"></HomeComponent>
    <!-- <NavbarComponent msg="Welcome"></NavbarComponent>
    <LandingComponent msg="Welcome"></LandingComponent> -->
  </div>
  
</template>

<script>
import HomeComponent from './components/HomeComponent.vue'
// import NavbarComponent from './components/NavbarComponent.vue'
// import LandingComponent from './components/LandingComponent.vue'

export default {
  name: "App",
  components: {
    HomeComponent,
    // NavbarComponent,
    // LandingComponent
  }
}
</script>

<style>

#app {
  font-family: Post Grotesk,Open Sans,sans-serif;
  font-size: 16px;
  line-height: 1.5;
  color: #fff;
  background-color: #000;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%
}

body {
  font-weight: 300;
  margin: 0;
}

* {
  box-sizing: border-box;
}

*, :after, :before {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

.container {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto
}

.container-fluid {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}

.container-fluid:after, .container-fluid:before {
  display: table;
  content: " ";
} 

.container-fluid:after {
  clear: both
} 

.row {
  margin-right: -15px;
  margin-left: -15px;
}

.row:after, .row:before {
  display: table;
  content: " ";
} 

.row:after {
  clear: both;
}

h1,h2,h3{
  /* font-family: Radikal OleSteen,Open Sans,sans-serif; */
  font-weight: 500;
  line-height: 1;
  color: #fff;
}

h1{
  font-size: 41px
}

h2{
  font-size: 34px
}

h3{
  font-size: 28px
}

.animate {
  animation-duration: 0.75s;
  animation-delay: 0.5s;
  animation-name: animate-fade;
  animation-timing-function: cubic-bezier(0.26, 0.53, 0.74, 1.48);
  animation-fill-mode: backwards;
}

.animate.pop {
  animation-name: animate-pop;
  animation-timing-function: ease;
}

@keyframes animate-pop {
  0% {
    opacity: 0;
    filter: brightness(3) saturate(3);
    transform: scale(0.5, 0.5);
  }

  100% {
    opacity: 1;
    filter: brightness(1) saturate(1);
    transform: scale(1, 1);
  }
}

.delay-1 {
  animation-delay: 0.6s;
}
.delay-2 {
  animation-delay: 0.7s;
}
.delay-3 {
  animation-delay: 0.8s;
}

</style>
