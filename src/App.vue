<script setup lang="ts">
// import { Icon } from '@iconify/vue';

</script>
<template>
  <div class="main">
    <div class="main-bg"> </div>
    <img class="main-bg-img" src="../src/assets/wall.jpg" alt="background">
    <div class="title">
      <div class="title__27b4dec39bd34515ad9bc848d0c530cc">AEVIO Digital</div>
    </div>

    <div class="sub">
      <div class="sub__21b4a304496c49d8903ab28eb0da8e08">Digital Content Creation</div>
    </div>

  </div>
</template>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  }
.main {
  position: relative;
  overflow: hidden;
  height: 100vh;
  width: 100vw;
  margin: 0;
  padding: 0;
  }
  .main-bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-color: rgba(0, 0, 0, 0.807);
    z-index: 2;
    overflow: hidden;
    margin: 0;
    padding: 0;
    }
    .main-bg-img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      object-fit: fill;
      opacity: 0.4;
      z-index: -1;
      overflow: hidden;
      margin: 0;
      padding: 0;
      }
            .sub {
              &__21b4a304496c49d8903ab28eb0da8e08 {
                font-family: Halyard Micro;
                font-size: 100px;
                font-weight: 700;
                font-style: italic;
                color: rgba(#fff, 0.39);
              }
            }
                        .title {
                          &__27b4dec39bd34515ad9bc848d0c530cc {
                            font-family: Halyard Micro;
                            font-size: 200px;
                            font-weight: 700;
                            font-style: italic;
                            color: rgba(#00fff6, 0.39);
                          }
                        }
</style>
