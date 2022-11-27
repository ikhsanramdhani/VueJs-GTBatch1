<template>
  <!-- After Product Left -->
  <div class="col-12 mt-5 p-5">
    <h3><b>Complete Your Room</b></h3>
    <h3><b>With What We Designed</b></h3>
    <div class="container-fluid d-flex justify-content-between" style="width: 100vw; height: 50vh">
      <Card v-for="(item, i) in arrCardTitle" :key="i" :cardPrice="arrCardPrice[i]" :cardImage="arrCardImage[i]" :cardTitle="item"></Card>
    </div>
    <div class="col-12 d-flex justify-content-center">
      <img src="./../assets/logo.png" alt="" />
    </div>
  </div>
  <!-- End After Product Left -->
</template>

<script>
import Card from "./Card.vue";

export default {
  name: "slider-component",
  components: {
    Card,
  },
  data() {
    return {
      arrCardPrice: ["89.300.000", "14.500.000", "22.000.000", "12.000.000"],
      arrCardImage: ["chair-4", "chair-3", "chair-2", "chair-1"],
      arrCardTitle: ["Cangkir Mauttie", "Saman Kakka", "Lino Dino", "Syail Ammino"],
    };
  },
};
</script>

<style></style>
