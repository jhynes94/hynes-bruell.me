<template>
  <div class="home">
    <Welcome/>
    <ProjectSearch/>
  </div>
</template>

<script>
import Welcome from '@/components/Welcome.vue'
import ProjectSearch from '@/components/projects/ProjectSearch.vue'

export default {
  name: 'Home',
  components: {
    Welcome,
    ProjectSearch,
  }
}
</script>
