<template>
  <div id="app" class="container">
    <Header />
    <router-view/>
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

*{
  font-family: 'Rubik', sans-serif;
  box-sizing: border-box;
}

div#app {
  height: 100vh;
}
</style>
