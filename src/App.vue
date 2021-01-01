<template>
  <div id="app">
    <appbar>
      <!-- Navbar -->
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <!-- Container wrapper -->
        <div class="container-fluid">
          <!-- Navbar brand -->
          <a class="navbar-brand" href="#">Analytics</a>

          <!-- Toggle button -->
          <button
            class="navbar-toggler"
            type="button"
            data-mdb-toggle="collapse"
            data-mdb-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <i class="fas fa-bars"></i>
          </button>

          <!-- Collapsible wrapper -->
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <!-- Left links -->
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <!-- Navbar -->
              <li class="nav-item">
                <router-link class="nav-link active" to="/">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/about">About</router-link>
              </li>
              <!-- Navbar dropdown -->
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="navbarDropdown"
                  role="button"
                  data-mdb-toggle="dropdown"
                  aria-expanded="false"
                >
                  Dropdown
                </a>
                <!-- Dropdown menu -->
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li>
                    <router-link class="dropdown-item" to="/catalog"
                      >Catalog</router-link
                    >
                  </li>

                  <li>
                    <router-link class="dropdown-item" to="/features"
                      >Features</router-link
                    >
                  </li>
                  <li><hr class="dropdown-divider" /></li>
                  <li>
                    <router-link class="dropdown-item" to="/trends"
                      >Trends</router-link
                    >
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <a
                  class="nav-link"
                  href="https://github.com/StephenBrooks220413"
                  target="_blank"
                  aria-disabled="true"
                  >Github</a
                >
              </li>
              <span class="icons">
                <li>
                  <a href="mailto:krammer439298@gmail.com">
                    <i class="nav-item far fa-envelope"></i>
                  </a>
                </li>
                <li>
                  <a href="tel:555-555-5555">
                    <i class="nav-item fas fa-mobile-alt"></i>
                  </a>
                </li>
              </span>
            </ul>
            <!-- Left links -->
          </div>
          <!-- Collapsible wrapper -->
        </div>
        <!-- Container wrapper -->
      </nav>
    </appbar>
    <router-view />
  </div>
</template>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
i {
  color: black !important;
}
#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.icons {
  display: flex;
  float: right !important;
  letter-spacing: 11px;
  padding-top: 3px;
  padding-left: 60px;
  font-size: 21px;
  color: blue !important;
}
.icons a {
  text-decoration: none !important;
  color: blue !important;
}
</style>
