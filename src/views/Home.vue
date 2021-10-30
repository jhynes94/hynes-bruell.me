<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <SnakeApp/>
  </div>
</template>

<script>
// @ is an alias to /src
import SnakeApp from '@/components/Snake.vue'

export default {
  name: 'Home',
  components: {
    SnakeApp
  }
}
</script>
