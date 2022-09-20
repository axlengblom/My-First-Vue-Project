<template>
  <div class="store">
    <h2>Welcome to the store</h2>
  </div>
</template>

<script>
export default {
  name: 'Store',
  props: {},
};
fetch('https://fakestoreapi.com/products/2')
  .then((res) => res.json())
  .then((json) => console.log(json));
</script>

<style scoped>
.store {
  height: auto;
  width: 100vw;
}
</style>
