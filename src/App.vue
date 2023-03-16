<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-white sticky-top">
      <div class="container">
        <router-link to="/" class="navbar-brand pb-3">
          <img src="./assets/Joblancer-logo.png" alt="" width="36" heighta="36" class="d-inline-block align-text-bottom me-2">
          <span class="fw-bold">JobLancer</span>
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto me-auto mb-2 mb-lg-0">
            <li class="nav-item px-md-3">
              <router-link to="/" class="nav-link">
                About Us
              </router-link>
            </li>
            <li class="nav-item px-md-3">
              <router-link to="/" class="nav-link">
                Features
              </router-link>
            </li>
            <li class="nav-item px-md-3">
              <router-link to="/" class="nav-link">
                Testimonials
              </router-link>
            </li>
          </ul>
          <ul class="d-flex">
            <router-link to="/login">
              <button class="btn btn-primary" type="submit">Sign In</button>
            </router-link>
          </ul>
        </div>
      </div>
    </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

</style>
