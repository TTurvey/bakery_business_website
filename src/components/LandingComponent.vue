<template>
    <div class="container m-0 p-0">
		<div class="landing-wrapper">

			<div class="logo-wrapper">
				<!-- <img class="logo-img" src="../../public/photos/nick-karvounis-jN_M0McVNeI-unsplash.jpg"> -->
				
				<div class="business-name-wrapper">
					<p class="business-name">
						<span class="business-name-1">CRUMBS</span>
						<br> 
						<span class="business-name-2">Bakery</span>
					</p>
				</div>
				
			</div>

			<div class="landing-image-wrapper">
				<div id="landing-photo"></div>
			</div>
		
		</div>
    </div>
</template>

<script>
export default {
  name: 'LandingComponent'
}
</script>


<style scoped>
	.landing-wrapper{
		display: inline-block;
		height: 80vh;
		width: 100vw;
		margin: 0 auto;
		overflow: hidden;
		border: 2px solid green;
	}

	.logo-wrapper{
		position: absolute;
		left: 0;
		text-align: center; 
		height: 80vh;
		width: 40%;

		margin: 0 auto;
		border: 2px solid blue;
		background: white;
		opacity: 0.1;
		z-index: 2;
	}

	.logo-wrapper:before {
		/* create a full-height inline block pseudo=element */
		content: ' ';
		display: inline-block;
		/* vertical alignment of the inline element */
		vertical-align: middle;  
		height: 100%;
	}

	.business-name-wrapper{
		display: inline-block;
		vertical-align: middle; 

		height: 20vh;
		width: 20vw;

		margin: 0 auto;
		border: 2px solid blue;
		background: white;
		
		z-index: 2;
	}

	.business-name-1{
		background-color: blue;
		font-size: 8vw;
	}

	.business-name-2{
		background-color: blue;
		font-size: 4vw;
	}


	#landing-photo {
		position: absolute;
		right: 0;

		height: 80vh;
		width: 70%;

		margin: 0 auto;
		border: 2px solid red;
		background-image: linear-gradient(to right, rgb(0, 0, 0), rgba(117, 19, 93, 0.1)), 
		url("../../public/photos/nick-karvounis-jN_M0McVNeI-unsplash.jpg");
		background-size: cover;
		z-index: 1;
	}

	.fade-in {
		opacity: 0;
		animation-name: fadeInOpacity;
		animation-delay: 1s;
		animation-duration: 3s;
		animation-iteration-count: 1;
		animation-timing-function: ease;
		animation-fill-mode: forwards;
	}

	@keyframes fadeInOpacity {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

</style>
