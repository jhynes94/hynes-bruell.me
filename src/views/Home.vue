<template>
  <div class="home">
    
    <OpeningRendering/>
    <Welcome />
    <ProjectSearch />

    <hr />
    <h1>Experience</h1>
    <div v-for="job in jobs" :key="job.companyName">
      <Experience :job="job"/>
    </div>

  </div>
</template>

<script>
import OpeningRendering from "@/components/OpeningRendering.vue";
import Welcome from "@/components/Welcome.vue";
import ProjectSearch from "@/components/projects/ProjectSearch.vue";
import Experience from "@/components/Experience.vue";
const workExperience = require("@/assets/workExperience.json");

export default {
  name: "Home",
  components: {
    Welcome,
    ProjectSearch,
    Experience,
    OpeningRendering,
  },
  data() {
    return {
      jobs: workExperience, //Gathered from external file
    };
  },
};
</script>
