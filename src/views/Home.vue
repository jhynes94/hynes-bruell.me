<template>
  <div class="home">
    
    <OpeningRendering/>
    <Welcome />
    <ProjectSearch />
    <Experience />

  </div>
</template>

<script>
import OpeningRendering from "@/components/OpeningRendering.vue";
import Welcome from "@/components/Welcome.vue";
import ProjectSearch from "@/components/projects/ProjectSearch.vue";
import Experience from "@/components/experience/Experience.vue";

export default {
  name: "Home",
  components: {
    Welcome,
    ProjectSearch,
    Experience,
    OpeningRendering,
  },
};
</script>
