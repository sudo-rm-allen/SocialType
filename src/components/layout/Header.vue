<template>
  <header class="header">
    <h1>MeetMe</h1>
    <div id="nav">
      <router-link to="/">Login</router-link>|
      <router-link to="/register">Register</router-link>|
      <router-link to="/about">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  background: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

.header a {
  color: white;
  padding-right: 5px;
  text-decoration: none;
}
</style>

