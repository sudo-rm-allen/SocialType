<template>
  <div class="home">
    <LoginForm/>
  </div>
</template>

<script>
// @ is an alias to /src
import LoginForm from "@/components/Signin_up.vue";
export default {
  name: "home",
  components: {
    //HelloWorld
    LoginForm
  }
};
</script>
