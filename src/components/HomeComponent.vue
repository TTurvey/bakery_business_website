<template>
  <div class="container__home">
    <div class="container-fluid">

      <div class="row">
        <div class="hero-container">
          <div class="hero-image animate pop delay-1" >
            <img class="hidden" src='../../src/assets/dana-nestorova-6_wAPQxXJQ4-unsplash.jpg' alt="" title="">
          </div>
          <div class="hero-container__inner hero-container__inner--content" scroll-fade="">
            <h2 class="hero-trumpet animate pop delay-2">Mmmmm...</h2>
            <h1 class="hero-headline animate pop delay-3">CRUMBS Bakery</h1>
            <!-- link to menu to be completed -->
            <a class="btn btn-primary btn-primary--hero" href="" title="Find Us">Find Us</a>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="block col-sm-6 col-xs-12">
          <div class="block__inner">
            <!-- link to menu to be completed -->
            <a class="block-link" href="" title="CAREERS">
              <div class="block-cover">
                <h3 class="block-cover-headline">CAREERS</h3>
              </div>
              <div class="block-image" id="block-careers">
                <img class="hidden" src='../../src/assets/tetiana-padurets-I5G_suhoqBQ-unsplash.jpg' alt="">
              </div>       
            </a>
          </div>
        </div>

        <div class="block col-sm-6 col-xs-12">
          <div class="block__inner">
            <!-- link to menu to be completed -->
            <a class="block-link" href="" title="ABOUT US">
              <div class="block-cover">
                <h3 class="block-cover-headline">ABOUT US</h3>
              </div>
              <div class="block-image" id="block-aboutus">
                <img class="hidden" src='../../src/assets/raul-angel-OnyIaAKUJfI-unsplash.jpg' alt="">
              </div>       
            </a>
          </div>
        </div>
      </div>

      <div class="block ">
          <div class="block__inner">
            <a class="block-link" href="" title="FIND A STORE">
              <div class="block-cover">
                <h3 class="block-cover-headline">FIND A STORE</h3>
              </div>
              <div class="block-image" id="block-findastore">
                <img class="hidden" src='../../src/assets/nick-karvounis-jN_M0McVNeI-unsplash.jpg' alt="">
              </div>
            </a>
          </div>
      </div>

      <div class="row">
        <div class="block col-sm-6 col-xs-12">
          <div class="block__inner">
            <!-- link to menu to be completed -->
            <a class="block-link" href="" title="MENU">
              <div class="block-cover">
                <h3 class="block-cover-headline">MENU</h3>
              </div>
              <div class="block-image" id="block-menu">
                <!-- <img class="hidden" src='../../src/assets/eaters-collective-Gg5-K-mJwuQ-unsplash.jpg' alt=""> -->
                <img class="hidden" src='../../src/assets/edward-howell-blGXrrVe1AU-unsplash.jpg' alt="">
              </div>
            </a>
          </div>
        </div>

        <div class="block col-sm-6 col-xs-12">
          <div class="block__inner">
            <a class="block-link" href="" title="CONTACT US">
              <div class="block-cover">
                <h3 class="block-cover-headline">CONTACT US</h3>
              </div>
              <div class="block-image" id="block-contactus">
                <img class="hidden" src='../../src/assets/edward-howell-blGXrrVe1AU-unsplash.jpg' alt="">
              </div>
            </a>
          </div>
        </div> 



      </div>
      
    </div>
  </div>

  
</template>

<script>
export default {
  name: 'HomeComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hidden {
  display: none !important;
}

img {
  vertical-align: middle;
}

.hero-container {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  height: 50vh;
  max-height: 512px;
  border: 1px solid blue;
}

.container__home .hero-container {
  height: 84.5vh;
  max-height: none
}

.hero-container__inner {
  position: relative;
  text-align: center;
  margin-top: 80px
}

.hero-container__inner--content {
  width: 62.5vw;
  -webkit-animation: fade .4s 1 cubic-bezier(.5,.11,.805,.32);
  animation: fade .4s 1 cubic-bezier(.5,.11,.805,.32)
}

.btn-primary--hero {
  margin-top: 20px
}

.hero-image {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  border: 1px solid red;
  background-image: url('../../src/assets/dana-nestorova-6_wAPQxXJQ4-unsplash.jpg');
  background-size: cover;
  background-position: center;
}

.hero-trumpet {
  font-size: 20px;
  line-height: 1.2;
  letter-spacing: 2px;
  margin: 0 0 15px
}

.hero-headline {
  font-size: 50px;
  line-height: 1.3;
  letter-spacing: 1.5px;
  text-align: center;
  margin: 0
}

.hero-container__inner--content .hero-headline {
  font-size: 100px;
  font-weight: bolder;
  line-height: 1.2;
  letter-spacing: 2px;
  text-shadow:
    0.01em 0 rgb(60, 60, 60),
    0 0.01em rgb(190, 190, 190),
    -0.01em 0 rgb(190, 190, 190),
    0 -0.01em rgb(190, 190, 190),
    -0.01em -0.01em rgb(190, 190, 190),
    -0.01em 0.01em rgb(190, 190, 190),
    0.01em -0.01em rgb(190, 190, 190),
    0.01em 0.01em rgb(190, 190, 190)
}

.btn {
  display: inline-block;
  color: #000;
  background: #fff;
  /* font-family: Radikal OleSteen,Open Sans,sans-serif; */
  font-weight: 500;
  font-size: 14px;
  line-height: 44px;
  letter-spacing: 2px;
  border: 0;
  padding: 0 28px;
  text-decoration: none;
  text-transform: uppercase
}

.btn:focus, .btn:hover {
  outline: none;
  text-decoration: none;
  color: #fff;
  background: #c09b4d
}

.block {
  margin-top: 10px;
  border: solid 2px red;
}

.block__inner {
  height: 100%;
  width: 100%;
  margin: 0 auto;
  text-align: center;
}

.block-link {
  position: relative;
  display: block;
  height: 300px;
  width: 100%;
}

.block-cover {
  position: absolute;
  top: 40px;
  left: 0;
  width: 100%;
  z-index: 1
}

.block-cover-headline {
  text-align: center;
  color: #fff;
  margin: 0;
  font-size: 30px;
  line-height: 1.2;
  letter-spacing: 2px
}

.block-image {
  background: 50%/cover no-repeat;
  height: 100%;
  width: 100%;
  /* background-image: url('../../src/assets/nick-karvounis-jN_M0McVNeI-unsplash.jpg'); */
  /* background-size: cover;
  background-position: center;
  background: no-repeat; */
}

#block-menu {
  background-image: url('../../src/assets/eaters-collective-Gg5-K-mJwuQ-unsplash.jpg');
}

#block-aboutus {
  background-image: url('../../src/assets/raul-angel-OnyIaAKUJfI-unsplash.jpg');
}

#block-careers {
  background-image: url('../../src/assets/tetiana-padurets-I5G_suhoqBQ-unsplash.jpg');
  /* background-image: url('../../src/assets/austin-ban-IS6RwpuEJpY-unsplash.jpg'); */
}

#block-findastore {
  background-image: url('../../src/assets/nick-karvounis-jN_M0McVNeI-unsplash.jpg');
}

#block-contactus {
  background-image: url('../../src/assets/edward-howell-blGXrrVe1AU-unsplash.jpg');
}

.col-sm-6, .col-xs-12 {
  position: relative;
  min-height: 1px;
  padding-right: 10px;
  padding-left: 10px;
}

@media (min-width: 768px) {
  .container {
      width:750px
  }
}

@media (min-width: 992px) {
  .container {
      width:970px
  }
}

@media (min-width: 1200px) {
  .container {
      width:1170px
  }
}

</style>