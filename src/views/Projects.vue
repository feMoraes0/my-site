<template>
  <div class="projects h-100 d-flex flex-column justify-content-center">
    <div class="row">
      <div class="col-md-6 d-flex flex-column justify-content-center">
        <PageTitle class="text-center mb-5">Projects</PageTitle>
        <div class="row mb-5">
          <div class="offset-md-2 col-md-8">
            <p class="w-100 text-center">
              Here you can see random four of my personal projects on
              <a
                target="_blank"
                href="https://www.github.com/femoraes0"
                class="link-dark text-decoration-none"
              ><strong>GitHub</strong></a>
            </p>
          </div>
        </div>

        <div class="row text-center links">
          <div class="col-6 mb-4">
            <ProjectCard
              label="javascript"
              title="starbucks-landing-page"
              content="VueJS Hiking Landing Page with animations"
            />
          </div>
          <div class="col-6 mb-4">
            <ProjectCard
              label="javascript"
              title="starbucks-landing-page"
              content="VueJS Hiking Landing Page with animations"
            />
          </div>
          <div class="col-6">
            <ProjectCard
              label="javascript"
              title="starbucks-landing-page"
              content="VueJS Hiking Landing Page with animations"
            />
          </div>
          <div class="col-6">
            <ProjectCard
              label="javascript"
              title="starbucks-landing-page"
              content="VueJS Hiking Landing Page with animations"
            />
          </div>
        </div>
      </div>
      <div class="offset-md-1 col-md-5 align-self-center">
        <img class="w-100" src="@/assets/images/lamps_graph.png" alt="lamps graph">
      </div>
    </div>
  </div>
</template>

<script>
import PageTitle from '@/components/PageTitle.vue';
import ProjectCard from '@/components/ProjectCard.vue';

export default {
  components: {
    PageTitle,
    ProjectCard,
  },
};
</script>

<style lang="scss" scoped>
.projects {
  p {
    font-size: 1.5rem;
  }
}
</style>
