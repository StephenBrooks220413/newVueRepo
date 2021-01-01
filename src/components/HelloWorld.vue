<template>
  <div class="container">
    <div class="jumbotron">
      <h1>Home Page</h1>
    </div>
    <div class="social-media">
      <i class="fab fa-twitter"></i>
      <i class="fab fa-facebook"></i>
      <i class="fab fa-github"></i>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
import { register } from "register-service-worker";

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.social-media i {
  font-size: 1.9em !important;
  padding-top: 45px;
  color: rgb(42, 42, 146) !important;
}
.social-media {
  letter-spacing: 35px;
}
.main {
  background: url(https://images.unsplash.com/photo-1606189934390-2b10bb7f8094?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 700px;
  padding-bottom: auto;
  width: 100%;
}
</style>
