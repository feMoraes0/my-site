<template>
  <div class="contact h-100 d-flex flex-column justify-content-center">
    <div class="row">
      <div class="col-md-5 align-self-center">
        <img class="w-100" src="@/assets/images/hands_ball.png" alt="hands ball">
      </div>
      <div class="offset-md-1 col-md-6  d-flex flex-column justify-content-center">
        <PageTitle class="text-center">Contact</PageTitle>
        <p class="w-100 text-center">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce et ex sit
          amet lacus ultrices elementum. Pellentesque vitae finibus tortor.
        </p>
        <div class="row text-center links">
          <div class="col-4">
            <a target="_blank" href="https://github.com">
              <img src="@/assets/icons/github.svg" alt="Github">
            </a>
          </div>
          <div class="col-4">
            <a target="_blank" href="https://www.linkedin.com/in">
              <img src="@/assets/icons/linkedin.svg" alt="LinkedIn">
            </a>
          </div>
          <div class="col-4">
            <a target="_blank" href="mailto:you@gmail.com">
              <img src="@/assets/icons/mail.svg" alt="Mail">
            </a>
          </div>
        </div>
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
.contact {
  p {
    font-size: 1.5rem;
    margin: 9.8vh 0;
  }

  .links {
    img {
      width: 60px;
      height: 60px;
    }
  }
}
</style>
