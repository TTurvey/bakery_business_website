<template>
  <div class="container m-0 p-0">
    <div class="left-door"></div>
    <div class="right-door"></div>
  </div>
</template>

<script>
export default {
  name: 'WelcomeComponent'
}
</script>


<style scoped>

  .container {
    display: flex;
  }

  .left-door {
    display: inline-block;
    position: absolute;
    z-index: 100;
    width: 50vw;
    height: 100vh;

    left: 0vw;
    background-color: rgb(38, 38, 38);
    opacity: 0.9;
  
    animation-name: slideout-left;
    animation-delay: 2s;
    animation-duration: 3s;
    animation-iteration-count: 1;
    animation-timing-function: ease;
    animation-fill-mode: forwards;
  }

  .right-door {
    display: inline-block;
    position: absolute;
    z-index: 100;
    width: 50vw;
    height: 100vh;

    left: 50vw;
    background-color: rgb(38, 38, 38);
    opacity: 0.9;
  
    animation-name: slideout-right;
    animation-delay: 2s;
    animation-duration: 3s;
    animation-iteration-count: 1;
    animation-timing-function: ease;
    animation-fill-mode: forwards;
  }

  @keyframes slideout-left {
    from { 
      left: 0vw;
      opacity: 0.9;
    }
    to { 
      left: -50vw;
      opacity: 0;
      display: none;
      visibility: hidden;
    }
  }

  @keyframes slideout-right {
    from { 
      left: 50vw;
      opacity: 0.9;
    }
    to { 
      left: 100vw;
      opacity: 0;
      display: none;
      visibility: hidden;
    }
  }

</style>
