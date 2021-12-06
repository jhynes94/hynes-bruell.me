<template>
  <div>
    <div class="exp">
      <p>{{job.companyName}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Welcome",
  props: {
    job: Object,
  },
  data() {
    return {
      // companyName: String,
      // jobDescription: String,
      // companyLogo: String,
      // startDate: Number,
      // endDate: Number,
      // jobPicture: String,
    };
  },
};
</script>