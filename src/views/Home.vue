<template>
  <div class="home h-100 d-flex flex-column justify-content-center">
    <div class="row">
      <div class="col-md-4  d-flex flex-column justify-content-center align-self-center">
        <PageTitle class="text-center">Title 1</PageTitle>
        <p class="w-100 text-center">
          Pellentesque vel egestas arcu, eget eleifend turpis. Aliquam sed orci
          consectetur, maximus enim at, eleifend lectus. Nullam facilisis mauris
          et vehicula placerat. Praesent vitae feugiat lorem. Duis luctus libero.
        </p>
      </div>
      <div class="col-md-4 align-self-center">
        <img class="w-100" src="@/assets/images/lamp_head.png" alt="lamp head">
      </div>
      <div class="col-md-4 d-flex flex-column justify-content-center align-self-center">
        <PageTitle class="text-center">Title 2</PageTitle>
        <p class=" w-100 text-center">
          Pellentesque vel egestas arcu, eget eleifend turpis. Aliquam sed orci
          consectetur, maximus enim at, eleifend lectus. Nullam facilisis mauris
          et vehicula placerat. Praesent vitae feugiat lorem. Duis luctus libero.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import PageTitle from '@/components/PageTitle.vue';

export default {
  components: {
    PageTitle,
  },
};
</script>

<style lang="scss" scoped>
.home {
  p {
    font-size: 1.5rem;
    margin-top: 40px;
  }
}
</style>
