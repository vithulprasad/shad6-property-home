<script setup lang="ts">

</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark w-full">
    <div class="container-fluid ">
      <div class="navbar-brand d-flex align-items-center">
        <img style="height: 60px; width: 60px;" src="assets/fcdb9af55e8fc03427fc844ffb3e6ab3-removebg-preview.png" alt="Logo"/>
        <h1 class="fs-3">Estatein</h1>
      </div>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse " id="navbarSupportedContent">
        <div class="navbar-nav mx-auto d-flex justify-content-around">
          <button type="button" class="btn btn-dark border border ">Home</button>
          <h1 class="fs-6 nav-item">About Us</h1>
          <h1 class="fs-6 nav-item">Properties</h1>
          <h1 class="fs-6 nav-item">Service</h1>
        </div>

        <div class="d-flex align-items-center">
          <button type="button" class="btn btn-dark border m-3">Contact Us</button>
        </div>
      </div>
    </div>
  </nav>
</template>
<style scoped>
  .navbar-nav.mx-auto.d-flex.justify-content-around{
    width:50%;

  }
  
</style>