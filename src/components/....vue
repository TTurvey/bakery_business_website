<template>
   
    
</template>

<script>
export default {
  name: 'HomeComponent'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.block {
    margin-top: 10px
}

.block__inner--image img {
    margin: 0 auto
}

.block__inner--text {
    padding: 35px 65px
}

.block__inner--center {
    text-align: center
}

.block-link {
    position: relative;
    display: block;
    height: 300px;
    width: 100%
}

.block-headline {
    font-size: 40px;
    line-height: 1.2;
    letter-spacing: 1px;
    margin: 0
}

.block-headline--spaced {
    margin-bottom: 20px
}

.col-single .block-headline {
    font-size: 50px;
    line-height: 1.3;
    letter-spacing: 1.5px;
    margin-bottom: 40px
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

.block-cover-subline {
    text-align: center;
    color: #fff;
    margin: 5px 0 0;
    font-size: 14px;
    line-height: 22px
}

.block-image {
    background: 50%/cover no-repeat;
    height: 100%;
    width: 100%
}

.block-content {
    margin-top: 10px
}

.block-content img {
    max-width: 100%
}



</style>