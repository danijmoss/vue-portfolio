<template>
  <div class="one main-content">
    <div class="left-content slideUp">
      <h1>CRYPTO LOGO</h1>

      <p class="subtxt">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed, impedit.</p>

      <router-link to="/portfolio/two">
        <img src="../assets/arrow-down.svg" class="arrow arrow-down">
      </router-link>
    </div>

    <div class="right-content img2">
      <img src="../assets/logo.svg">
    </div>
  </div>
</template>

<script>
export default {
  name: "one"
};
</script>

<style lang="scss" scoped>
$page_color: #625b7e;

h1 {
  color: $page_color !important;
}

.img2 {
  background: $page_color;

  img {
    width: 50%;
  }
}
</style>
