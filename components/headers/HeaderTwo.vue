<script setup lang="ts">

</script>

<template>
  <nav class="navbar navbar-expand-lg w-full p-0">
    <div class="container-fluid ">
      <div class="navbar-brand d-flex align-items-center">
        <svg xmlns="http://www.w3.org/2000/svg" width="48" height="49" viewBox="0 0 48 49" fill="none">
          <path d="M24 48.5C10.7467 48.5 0 37.7533 0 24.5H24V48.5Z" fill="#703BF7"/>
          <path d="M0 0.5C13.2533 0.5 24 11.2467 24 24.5H0V0.5Z" fill="#703BF7"/>
          <path d="M24 48.5C37.2533 48.5 48 37.7533 48 24.5H24V48.5Z" fill="#703BF7"/>
          <path d="M48 24.5C48 11.2467 37.2533 0.5 24 0.5V24.5H48Z" fill="#703BF7"/>
        </svg>
        <h1 class="fs-3">Estatein</h1>
      </div>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse " id="navbarSupportedContent">
        <div class="navbar-nav mx-auto d-flex ">
          <button type="button" class="btn btn-dark   ">Home</button>
          <h1 class="fs-6 nav-item pt-2 mx-3">About Us</h1>
          <h1 class="fs-6 nav-item pt-2 mx-3">Properties</h1>
          <h1 class="fs-6 nav-item pt-2 mx-3">Service</h1>
        </div>

        <div class="d-flex align-items-center">
          <button type="button" class="btn btn-dark  m-3">Contact Us</button>
        </div>
      </div>
    </div>
  </nav>
</template>
<style scoped>
  .navbar-nav.mx-auto.d-flex.justify-content-around{
    width:50%;

  }
  h1{
    color: aliceblue;
  }
  .navbar.navbar-expand-lg.w-full{
    background-color: rgb(27, 26, 26);
  }
  button {
 border-color: black;
 background: var(--Grey-08, #141414)
}

</style>