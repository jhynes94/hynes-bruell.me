<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">Projects</router-link> |
    <router-link to="/about">Experience</router-link> |
    <router-link to="/about">Contact</router-link>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style scoped>

#nav {
  background-color: #87C0B4;
  width: 100%;
  padding: 10px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

</style>