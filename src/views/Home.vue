<template>
  <div class="home">
    <h1>3D Rendering here</h1>
    <SnakeApp/>
  </div>
</template>

<script>
// @ is an alias to /src
import SnakeApp from '@/components/Snake.vue'

export default {
  name: 'Home',
  components: {
    SnakeApp,
  } 
}
</script>
