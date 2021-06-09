<template>
  <div class="home h-100 d-flex flex-column justify-content-center">
    <div class="row">
      <div class="col-md-4  d-flex flex-column justify-content-center align-self-center">
        <PageTitle class="text-center">Front End</PageTitle>
        <p class="w-100 text-center">
          Moved by how to provide the best user experience without lose performance
          and code maintainability for mobile and web applications. Currently using
          preferable, but not only, JavaScript libraries and framerwors.
        </p>
      </div>
      <div class="col-md-4 align-self-center">
        <img class="w-100" src="@/assets/images/lamp_head.png" alt="lamp head">
      </div>
      <div class="col-md-4 d-flex flex-column justify-content-center align-self-center">
        <PageTitle class="text-center">Back End</PageTitle>
        <p class=" w-100 text-center">
          Focused in delivery well integrated systems with optimizations in time and
          space without compromise the functionalities, requirements, legibility or security;
          Using almost exclusively JavaScript and Typescript.
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
