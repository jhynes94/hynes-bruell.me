<template>
  <div>
    <h1>Project Search</h1>
    <h2>Tags</h2>
    <ul>
      <li>Electrical</li>
      <li>Software</li>
      <li>Business</li>
    </ul>
    <h3>List of projects with links</h3>

    <h1>Full time Experience</h1>
    <div v-for="project in projects" :key="project.name">
      <Project :project="project" />
    </div>

  </div>
</template>

<script>
import Project from "@/components/projects/Project.vue";
const projectData = require("@/assets/projectsData.json");

export default {
  name: "ProjectsSearch",
  components: {
    Project,
  },
  data() {
    return {
      projects: projectData, //import JSON data from external file to "projects"
    };
  },
};
</script>