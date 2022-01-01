<template>
<div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="./assets/logo.png" width="50px" alt="" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation">
  <span class="navbar-togler-icon" id="navbarSupportedContent"></span>
  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
    <router-link tag="li" class="nav-item" to="/">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </router-link>

             <router-link tag="li" class="nav-item" to="/about">
              <a class="nav-link active" aria-current="page" href="#">About</a>
            </router-link>

             <router-link tag="li" class="nav-item" to="/contact">
              <a class="nav-link active" aria-current="page" href="#">Contact</a>
            </router-link>

             <router-link tag="li" class="nav-item" to="/auth">
              <a class="nav-link active" aria-current="page" href="#">Auth</a>
            </router-link>
          </ul>
  
  </div>
</template>

<script>
export default {
 
}
</script>

<style>



</style>
