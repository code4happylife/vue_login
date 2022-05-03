<template>
  <LoginBox></LoginBox>
</template>

<script>
import LoginBox from "@/components/LoginBox";

export default {
  name: 'App',
  components: {
    LoginBox
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
