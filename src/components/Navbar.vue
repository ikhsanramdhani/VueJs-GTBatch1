<template>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid px-5">
      <a class="navbar-brand" href="#"><img src="./../assets/logo.png" alt="Luxspace" /></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Showcase</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Catalog</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Delivery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Rewards</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><img src="./../assets/cart-icon.png" alt="Cart" /></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- End Navbar -->
</template>

<script>
export default {
  name: "navbar-component",
};
</script>

<style></style>
