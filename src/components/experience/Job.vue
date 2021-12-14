<template>
  <div>
    <div class="exp">
      <p>{{job.companyName}}</p>
      <p>{{job.description}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Job",
  props: {
    job: Object,
  },
};
</script>