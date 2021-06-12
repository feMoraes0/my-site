<template>
  <div id="app" class="container">
    <Header />
    <transition name="default" mode="out-in">
      <router-view></router-view>
    </transition>

  </div>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'Home',
  components: {
    Header,
  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap');

* {
  font-family: 'Rubik', sans-serif;
  box-sizing: border-box;
}

div#app {
  height: 100vh;
}

$animation-duration: 1000ms;
$default-colour: #212529;

.default-enter-active, .default-leave-active {
  transition: all 1s ease;
}

.default-leave, .default-enter-to {

  &:after {
    content: "";
    z-index: 2;
    background-color: $default-colour;
    position: fixed;
    top: calc(50% - .5px);
    left: calc(50% - .5px);
    width: 1px;
    height: 1px;
    border-radius: 100%;
    transform: scale(100%);
    transition-duration: $animation-duration;
  }
}

.default-leave-to, .default-enter {
  &:after {
    content: "";
    z-index: 2;
    background-color: $default-colour;
    position: fixed;
    top: calc(50% - 50px);
    left: calc(50% - 50px);
    width: 100px;
    height: 100px;
    border-radius: 100%;
    transform: scale(2000%);
    transition-duration: $animation-duration;
  }
}
</style>
