<template>
  <div
    class="
      project-card bg-dark
      rounded text-start p-3 d-flex
      flex-column align-items-start
      justify-content-md-between
    "
  >
    <span class="text-white">{{label}}</span>
    <h4 class="text-white my-3">{{title}}</h4>
    <p class="text-white mb-0">{{content}}</p>
  </div>
</template>

<script>
export default {
  name: 'ProjectCard',
  props: {
    label: {
      required: true,
      type: String,
    },
    title: {
      required: true,
      type: String,
    },
    content: {
      required: true,
      type: String,
    },
  },
};
</script>

<style lang="scss" scoped>
.project-card {
  span {
    font-size: 1rem;
    line-height: 1.25rem;
  }

  h4 {
    font-size: 1.3125rem;
    line-height: 1.5625rem;
  }

  p {
    font-style: normal;
    font-size: 0.875rem;
  }
}
</style>
