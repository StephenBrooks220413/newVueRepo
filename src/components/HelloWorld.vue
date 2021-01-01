<template>
  <div class="hello">
    <div class="jumbotron main">
      <h1 class="display-4">
        Site Analytics to find the best organic traffic for you.
      </h1>
    </div>
    <div class="social-media">
      <h1 class="text-center">Follow Us</h1>
      <i class="fab fa-twitter"></i>
      <i class="fab fa-facebook"></i>
      <i class="fab fa-github"></i>
    </div>
    <div class="jumbotron content-1">
      <h1 class="display-4">
        Data driven results from social media to drive traffic.
      </h1>
    </div>
    <div class="container table">
      <h1 class="text-center">Our Analytics As of 2020</h1>
      <br />
      <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Quarter</th>
            <th scope="col">semin-annual</th>
            <th scope="col">annually</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>5,346 visitors</td>
            <td>10,692 visitors</td>
            <td>32,000 visitors</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>12 countries</td>
            <td>27 countries</td>
            <td>33 countries</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>78 form subissions</td>
            <td>230 form submissions</td>
            <td>610 form submissions</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="jumbotron content-2">
      <h1 class="display-4">
        Proven results from client to client and their bottom lines.
      </h1>
    </div>
    <br />
    <div class="container">
      <h1 class="text-center">Our Team</h1>
      <br /><br />
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">CEO / Owner</h5>
              <img
                src="https://images.unsplash.com/photo-1562788869-4ed32648eb72?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80"
                alt="business"
                width="120px"
                height="120px"
              />
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
        <br />
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Vice President</h5>
              <img
                src="https://images.unsplash.com/photo-1562788869-4ed32648eb72?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80"
                alt="business"
                width="120px"
                height="120px"
              />
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
        <br />
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Sales Manager</h5>
              <img
                src="https://images.unsplash.com/photo-1562788869-4ed32648eb72?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80"
                alt="business"
                width="120px"
                height="120px"
              />
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br /><br /><br />
    <div class="jumbotron content-3">
      <h1 class="display-4">
        Peak hours are always stable and off times are still ongoing.
      </h1>
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
  padding: 15px;
  color: rgb(189, 189, 197) !important;
}
.social-media {
  letter-spacing: 35px;
  background-color: rgb(255, 255, 255);
  width: 100%;
  margin-bottom: 25px;
}
.social-media h1 {
  letter-spacing: 5px !important;
}
.main {
  background: url(https://images.unsplash.com/photo-1606189934390-2b10bb7f8094?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 20%;
  padding-bottom: 20%;
  width: 100%;
}
.main-img {
  max-width: 700px;
  max-height: 610px;
  margin-left: auto;
  margin-right: auto;
}
.content-1 {
  background: url(https://images.unsplash.com/photo-1596705280787-7c2b0618b0aa?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=979&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 20%;
  padding-bottom: 20%;
  width: 100%;
}
.table {
  margin-top: 20px !important;
  margin-bottom: 27px !important;
}
.content-2 {
  background: url(https://images.unsplash.com/photo-1596737093717-df20722bf5ef?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1049&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 20%;
  padding-bottom: 20%;
  width: 100%;
}
.content-3 {
  background: url(https://images.unsplash.com/photo-1599413722590-6d5f382480db?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 20%;
  padding-bottom: 20%;
  width: 100%;
}
img {
  border-radius: 50% !important;
}
</style>
