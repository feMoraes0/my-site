<template>
  <div class="about h-100 d-flex flex-column justify-content-center">
    <div class="row">
      <div class="col-md-5 align-self-center">
        <img class="w-100" src="@/assets/images/fish_man.png" alt="fish man">
      </div>
      <div class="offset-md-1 col-md-6  d-flex flex-column justify-content-center">
        <PageTitle class="text-center mb-5">About</PageTitle>
        <p class="w-100 text-center">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus rhoncus enim id eros facilisis, in eleifend erat maximus.
          In pellentesque tortor sit amet pellentesque tincidunt. Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Phasellus rhoncus enim id eros facilisis, in eleifend erat
          maximus. In pellentesque tortor sit amet pellentesque tincidunt.
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
.about {
  p {
    font-size: 1.5rem;
  }
}
</style>
