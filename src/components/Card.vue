<template>
  <div class="col-2">
    <img :src="require('@/assets/' + cardImage + '.png')" alt="Chair 1" />
    <h6 class="mt-2">
      <b>{{ cardTitle }}</b>
    </h6>
    <p>IDR {{ cardPrice }}</p>
  </div>
</template>

<script>
export default {
  name: "card-component",
  props: ["cardTitle", "cardPrice", "cardImage"],
};
</script>

<style></style>
