<template>
  <h1><slot></slot></h1>
</template>

<script>
export default {
  name: 'PageTitle',
};
</script>

<style lang="scss" scoped>
  h1 {
    font-size: 70px;
    font-weight: 700;
  }
</style>
