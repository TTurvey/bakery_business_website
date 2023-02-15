<template>
  <div class="container m-0 p-0">
    <img src="../../public/photos/nick-karvounis-jN_M0McVNeI-unsplash.jpg" class="fade-in" id="landing-photo">
  </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>


<style scoped>
	#landing-photo{
	height: auto;
	width: 100vw;
	margin: 0 auto;
	}

	.fade-in {
		opacity: 0;
		animation-name: fadeInOpacity;
		animation-delay: 2s;
		animation-duration: 3s;
		animation-iteration-count: 1;
		animation-timing-function: ease;
	}

	@keyframes fadeInOpacity {
		0% {
			opacity: 0;
			transform: scale(1, 1);
		}
		100% {
			opacity: 1;
			transform: scale(1.05, 1.05);
		}
	}

</style>
