import { register } from 'register-service-worker';
<template>
  <div class="container">
    <div class="jumbotron">
      <h1>Catalog Page</h1>
    </div>
    <div class="social-media">
      <i class="fab fa-twitter"></i>
      <i class="fab fa-facebook"></i>
      <i class="fab fa-github"></i>
    </div>
    <br /><br /><br /><br />
    <div class="container text-center">
      <h1>Rep for this app <i class="fas fa-code-branch"></i></h1>
      <br /><br /><br /><br />
      <div class="container card-container">
        <div class="row">
          <div class="col-md-4">
            <div class="card" style="width: 100%">
              <div class="card-body">
                <h2 class="card-title">Special title treatment</h2>
                <br />
                <i class="fas fa-blender-phone"></i>
                <p class="card-text">
                  <br />
                  With supporting text below as a natural lead-in to additional
                  content.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card" style="width: 100%">
              <div class="card-body">
                <h2 class="card-title">Special title treatment</h2>
                <br />
                <i class="fab fa-angellist"></i>
                <p class="card-text">
                  <br />
                  With supporting text below as a natural lead-in to additional
                  content.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card" style="width: 100%">
              <div class="card-body">
                <h2 class="card-title">Special title treatment</h2>
                <br />
                <i class="fas fa-briefcase"></i>
                <p class="card-text">
                  <br />
                  With supporting text below as a natural lead-in to additional
                  content.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.social-media i {
  font-size: 1.9em !important;
  padding-top: 45px;
  color: rgb(42, 42, 146) !important;
}
.social-media {
  letter-spacing: 35px;
}
.about {
  padding-top: 10px;
}
.card-container {
  padding-bottom: 90px;
}
.card {
  margin-bottom: 10px !important;
}
i {
  font-size: 2em !important;
}
h1 i {
  font-size: 1em !important;
}
li {
  list-style: none;
}
</style>
