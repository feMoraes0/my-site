<template>
<div class="header position-relative d-flex flex-row align-items-center">
  <div class="row w-100">
    <div
      class="
        col-md-8 offset-md-2
        d-flex flex-row justify-content-around align-items-center
      "
    >
      <router-link class="text-dark text-decoration-none" to="/about">About</router-link>
      <router-link class="text-dark text-decoration-none" to="/contact">Contact</router-link>
      <router-link class="text-dark text-decoration-none" to="/">Home</router-link>
      <router-link class="text-dark text-decoration-none" to="/experiences">
        Experiences
      </router-link>
      <router-link class="text-dark text-decoration-none" to="/projects">Projects</router-link>
    </div>
  </div>
</div>
</template>

<style lang="scss" scoped>
.header {
  height: 12%;
}
</style>
