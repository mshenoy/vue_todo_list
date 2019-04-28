<template>
  <header>
    <h1>Todo List</h1>
    <router-link to="/">Home</router-link>|
    <router-link to="/about">About</router-link>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
header {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1rem;
}

h1 {
  margin-bottom: 0.5rem;
}

header a {
  color: #fff;
  padding-right: 5px;
}
</style>


