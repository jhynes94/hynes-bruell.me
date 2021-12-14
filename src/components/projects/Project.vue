<template>
  <div>
    <div class="exp">
      <p>{{project.name}}</p>
      <p>{{project.description}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Project",
  props: {
    project: Object,
  },
};
</script>