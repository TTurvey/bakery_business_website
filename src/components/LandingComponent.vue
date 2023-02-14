<template>
  <div class="container-fluid">
    <img src="../../public/photos/nick-karvounis-jN_M0McVNeI-unsplash.jpg" class="fade-in" id="landing-photo">
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#landing-photo{
  height:100vh;
  width: 100%;
}

.fade-in {
	opacity: 1;
	animation-name: fadeInOpacity;
	animation-iteration-count: 1;
	animation-timing-function: ease-in;
	animation-duration: 3s;
}

@keyframes fadeInOpacity {
	0% {
		opacity: 0.1;
	}
	100% {
		opacity: 1;
	}
}
</style>
