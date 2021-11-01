<template>
  <div class="home">
    <NavBar/>
    <h1>3D Rendering here</h1>
    <SnakeApp/>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'
import SnakeApp from '@/components/Snake.vue'

export default {
  name: 'Home',
  components: {
    SnakeApp,
    NavBar
  } 
}
</script>
