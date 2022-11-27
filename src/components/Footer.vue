<template>
  <div class="container-fluid d-flex justify-content-around" style="width: 100vw; height: 30vh">
    <div class="col-2 d-flex justify-content-center" style="width: 15vw; height: 15vh">
      <div class="d-flex flex-column">
        <h4>Overview</h4>
        <a class="text-dark" href="#">Shipping</a>
        <a class="text-dark" href="#">Refund</a>
        <a class="text-dark" href="#">Promotion</a>
      </div>
    </div>

    <div class="col-2 d-flex justify-content-center" style="width: 15vw; height: 15vh">
      <div class="d-flex flex-column">
        <h4>Company</h4>
        <a class="text-dark" href="#">About</a>
        <a class="text-dark" href="#">Career</a>
        <a class="text-dark" href="#">Contact Us</a>
      </div>
    </div>

    <div class="col-2 d-flex justify-content-center" style="width: 15vw; height: 15vh">
      <div class="d-flex flex-column">
        <h4>Explore</h4>
        <a class="text-dark" href="#">Terms & Conds</a>
        <a class="text-dark" href="#">Privacy Policy</a>
        <a class="text-dark" href="#">For Developer</a>
      </div>
    </div>

    <div class="col-4" style="width: 15vw; height: 15vh">
      <h4>Special Letter</h4>
      <form class="form-inline">
        <input class="form-control mr-sm-2" type="search" placeholder="Your Email Address" aria-label="Search" />
        <button class="btn my-2 my-sm-0 bg-danger disabled" type="submit">
          <img src="./../assets/tele-icon.png" alt="Tele" />
        </button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "footer-component",
};
</script>

<style></style>
