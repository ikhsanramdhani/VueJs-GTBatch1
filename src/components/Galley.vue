<template>
  <!-- Main Product -->
  <div class="container-fluid d-flex mt-4 justify-content-between">
    <!-- Left -->
    <div class="col-2" style="width: 10vw; height: 80vh">
      <div class="d-flex flex-column align-items-end mt-5">
        <div class="p-1 py-3">
          <img src="./../assets/side-1.png" class="rounded" alt="Side 1" style="width: 5vw" />
        </div>
        <div class="p-1 py-3">
          <img src="./../assets/side-2.png" class="rounded" alt="Side 2" style="width: 5vw" />
        </div>
        <div class="p-1 py-3">
          <img src="./../assets/side-3.png" class="rounded" alt="Side 3" style="width: 5vw" />
        </div>
        <div class="p-1 py-3">
          <img src="./../assets/side-1.png" class="rounded" alt="Side 4" style="width: 5vw" />
        </div>
        <div class="p-1 py-3">
          <img src="./../assets/side-2.png" class="rounded border border-dark" alt="Side 5" style="width: 5vw" />
        </div>
      </div>
    </div>

    <!-- Center -->
    <div class="col-5" style="width: 10vw; height: 85vh">
      <div class="d-flex flex-column mt-2">
        <div class="p-0 pr-4">
          <img src="./../assets/chair.png" class="rounded" alt="chair" />
        </div>
      </div>
    </div>

    <!-- Right -->
    <div class="col-4" style="width: 10vw; height: 55vh">
      <h1 class="mt-4">Chair Thatty</h1>
      <p>IDR 12.000.000</p>
      <button type="submit" class="px-4 p-2" style="background-color: pink; border-style: none; border-radius: 10px"><img src="./../assets/cart-icon.png" class="mr-2" alt="cart" /><b> Add to cart</b></button>
      <hr />
      <p><b>About the product:</b></p>
      <p>Tailored to a level of perfection synonymous with that of a Savile Row suit and with understated quality in the detail, Jetty has been influenced by timeless 1950s style.</p>
      <p>Providing a subtle nod to the past, Jetty also provides a perfect solution for the way we work today. A compherensive product family, Jetty features a variety of elegant chairs and sofas.</p>
    </div>
  </div>
  <!-- End Main Product -->
</template>

<script>
export default {
  name: "galley-component",
};
</script>

<style></style>
