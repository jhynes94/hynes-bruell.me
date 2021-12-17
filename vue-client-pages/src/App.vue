<template>
  <Nav />
  <router-view/>
</template>

<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'

export default {
  name: 'App',
  components: {
    Nav
  }
}
</script>

<style>
/* https://coolors.co/87a5c0 */
body{
  margin: 0px;
  background-color: white;
}

#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

hr{
  border: solid 1px;
}


.button {
  background-color: #C0A187;
}
</style>
