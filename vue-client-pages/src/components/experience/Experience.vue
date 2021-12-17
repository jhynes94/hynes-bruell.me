<template>
  <div>
    <h1>Full time Experience</h1>
    <div v-for="job in jobs" :key="job.companyName">
      <Job :job="job"/>
    </div>
  </div>
</template>

<script>
import Job from "@/components/experience/Job.vue";
const workExperience = require("@/assets/workExperience.json");


export default {
  name: "Welcome",
  components: {
    Job,
  },
  data() {
    return {
      jobs: workExperience, //Gathered from external file
    };
  },
};
</script>