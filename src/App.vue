<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link class="router" to="/">Home</router-link>
      <router-link class="router" to="/Register">Register</router-link>
      <router-link class="router" to="/about">About</router-link>
    </div>-->
    <Header/>
    <router-view/>
  </div>
</template>


<script>
import Header from "./components/layout/Header";
export default {
  name: "app",
  components: {
    Header
  }
};
</script>


<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
